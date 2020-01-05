# qt-ffmpeg
	http://ffmpeg.org/
 Research drives learning, Develop an easy-to-understand player with perfect functions from zero based on ffmpeg.

1. ##configure
    > ###from INSTALL.md
    >
    >`configure` can be launched from a directory  different from the FFmpeg
sources to build the objects out of tree. To do this, use an absolute
path when launching `configure`, e.g. `/ffmpegdir/ffmpeg/configure`.
	
	####$ /home/m2n/qt-ffmpeg/ffmpeg-src/configure --prefix=/home/m2n/qt-ffmpeg/ffmpeg-src-output --enable-shared --docdir=/home/m2n/qt-ffmpeg/ffmpeg-src-output/ffmepg-doc
or
	https://cloud.tencent.com/developer/article/1409522
	####$ /home/m2n/qt-ffmpeg/ffmpeg-src/configure  --enable-shared --enable-gpl --enable-pthreads --enable-libx264 --enable-libx265 --enable-librtmp

2. ##make
	####$ make

3. ##make install
	####$ make install














