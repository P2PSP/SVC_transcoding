# SVC_transcoding

[![Join the chat at https://gitter.im/P2PSP/SVC_transcoding](https://badges.gitter.im/P2PSP/SVC_transcoding.svg)](https://gitter.im/P2PSP/SVC_transcoding?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Scalable Video Transcoding for OGG streams

Similarly to the [MDC transcoder](https://github.com/P2PSP/MDC_transcoding), a Scalable Video Coding (SVC) transcoder could improve the performance in variable-bandwidth scenarios. In this case, the forward transcoder would input an OGG stream and output a number of layers (OGG streams), each one presenting a different level of a Laplacian Pyramid.

The inverse transcoder would reconstruct the original OGG sequence (or an approximation of it) using all (or a smaller number of) layers.
