git clone git@github.com:WeiyiGeek/imagesbuild.gitmkdir -vp action-sync-images/sig-storage/nfs-subdir-external-provisionertee action-sync-images/sig-storage/nfs-subdir-external-provisioner/Dockerfile  <<'EOF'
FROM k8s.gcr.io/sig-storage/nfs-subdir-external-provisioner:v4.0.2
LABEL MAINTAINER=master@weiyigeeek.top BUILDTYPE=Aliyun
EOFgit add . && git commit -m "nfs-subdir-external-provisioner" && git push
