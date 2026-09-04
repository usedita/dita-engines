# dita-engines

Os motores locais que o [Dita](https://usedita.com) baixa quando você escolhe
"Local" na Transcrição: `dita-whisper` (o `whisper-server` do
[whisper.cpp](https://github.com/ggml-org/whisper.cpp)) e `dita-llm` (o
`llama-server` do [llama.cpp](https://github.com/ggml-org/llama.cpp)),
compilados sem modificação de código, estáticos, assinados com o Developer ID
do Dita e notarizados pela Apple. Um pacote por arquitetura, em
[Releases](https://github.com/usedita/dita-engines/releases).

Este repositório existe só para hospedar os pacotes e o `manifest.json`
(versões, URLs e sha256), que o app confere antes de usar qualquer arquivo.
O código do Dita não mora aqui.

The local engines the [Dita](https://usedita.com) dictation app downloads when
you pick "Local" for transcription: `dita-whisper` (whisper.cpp's
`whisper-server`) and `dita-llm` (llama.cpp's `llama-server`), built unmodified,
statically linked, signed and notarized. One package per architecture, under
Releases. This repository only hosts the packages and the `manifest.json` the
app verifies against; Dita's source does not live here.

Licenças: whisper.cpp e llama.cpp são MIT (Georgi Gerganov e colaboradores);
as licenças vão dentro de cada pacote, em `LICENSES/`.
