**git的最基本作用是版本控bai制，比如你写一个文档，老板du一直让你改，这时笨的人会在原zhi文档上直接改，聪明dao一点的会复制一下原文档，在副本上修改，这时老板说你的第三版比较好，笨的人煞笔了。。，聪明一点的就直接拷贝了第三版给客户发过去了。然后聪明一点的认为这次的事情完事了把其他没用的都删了，突然有一天老板说客户的意见和你最后一版的相同，这时聪明一点的人也煞笔了。。。。来了个最聪明的人，会用git,他在本地建了一个版本库，每次老板让他修改，他就把之前的版本提交一下，并标明这版的主要特点，这样文件夹里就只有一个文档，每次老板说要那个版本的，他就直接从版本库里恢复一下。git通常在编程中会用到，通常是多个人同时协作一个项目，有可能出现两个人同时修改一个文件，这时后提交的人会遇到冲突，需要解决冲突；git能够记录每个人的提交修改等形成日志，可以根据提交记录进行回滚；并且git支持分布式部署。**

**你执行的 Git 操作，几乎只往 Git 数据库中 添加 数据。 你很难让 Git 执行任何不可逆操作，或者让它以任何方式清除数据。 同别的 VCS 一样，未提交更新时有可能丢失或弄乱修改的内容。但是一旦你提交快照到 Git 中， 就难以再丢失数据，特别是如果你定期的推送数据库到其它仓库的话。这使得我们使用 Git 成为一个安心愉悦的过程，因为我们深知可以尽情做各种尝试，而没有把事情弄糟的危险。 **