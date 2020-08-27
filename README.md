# silk
转码命令


ffmpeg -i [mp3_path] -f s16le -ar 24000 -ac 1 -acodec pcm_s16le [tmp_path]


encoder [tmp_path] [silk_path] -tencent


其中encoder来自https://github.com/kn007/silk-v3-decoder
