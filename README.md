# 声网的demo 做了信令拨号通话视频（已修正为studio工程）
1. so库从视频处全部copy过来， 目录： app/libs/*.jar  app/src/main/jniLibs/arm*, 对应的库从视频demo拷贝黏贴此处，so太大上传不了
2. onFirstRemoteVideoDecoded 的回调修改成在UI线程中执行
3. enableMediaCertificate 修改成true
4. appID  和 certificate去官网注册产生

# 操作步骤
1. A用户先点，Speaker, video, 选中 login => 等待
2. B用户点击switch， Speaker video 选中，然后点击login
3. A用户点击CALL 呼叫B 

DONE
