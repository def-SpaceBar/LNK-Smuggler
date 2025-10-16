## 📘 CLI Help

<details open>
<summary><strong>Show command usage</strong></summary>

```console
python lnk-builder-v2-wip.py -h
usage: lnk-builder-v2-wip.py [-h] -mode
                             {downloader,smuggle,smuggle_memory_load,zip_downloader}
                             [-download_link DOWNLOAD_LINK]
                             [-payload_path PAYLOAD_PATH]
                             [-extension EXTENSION]
                             [-decoy_path DECOY_PATH]
                             [-self_destruct {replace_with_decoy,delete}]
                             [-output_file_name OUTPUT_FILE_NAME]
                             [-icon {image,image2,folder,browser,video,audio,pdf,txt}]
                             [-view_mode {hidden-window,full-size-window,normal-size-window}]

options:
  -h, --help
  -mode {downloader,smuggle,smuggle_memory_load,zip_downloader}
  -download_link DOWNLOAD_LINK
  -payload_path PAYLOAD_PATH
  -extension EXTENSION
  -decoy_path DECOY_PATH
  -self_destruct {replace_with_decoy,delete}
  -output_file_name OUTPUT_FILE_NAME
  -icon {image,image2,folder,browser,video,audio,pdf,txt}
  -view_mode {hidden-window,full-size-window,normal-size-window}
