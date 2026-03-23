FROM gcr.io/oss-fuzz-base/base-builder-go@sha256:b94960b04ba0d6742e5c63dc66bfa49f58fef733a5e6c0ec63c2348a7773b114
COPY . $SRC/atlantis
COPY .clusterfuzzlite/build.sh $SRC/build.sh
WORKDIR $SRC/atlantis
