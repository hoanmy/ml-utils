# visdrone

$ sh gdrive_download.sh 1PFdW_VFSCfZ_sTSZAGjQdifF_Xd5mf0V VisDrone2019-DET-test-dev.zip

$ python3 convertVis_to_xml.py

$ python3 voc2coco-simple.py <dir/annotations/> <dir/output.json>

$ python3 voc2coco-complex.py --ann_paths_list </dir/paths of annotation folder.txt> --labels </dir/labels.txt> --output </dir/output.json>

$ python voc2coco-complex.py \
    --ann_dir /path/to/annotation/dir \
    --ann_ids /path/to/annotations/ids/list.txt \
    --labels /path/to/labels.txt \
    --output /path/to/output.json \
    <option> --ext xml

$ python voc2coco-complex.py \
    --ann_paths_list /path/to/annotation/paths.txt \
    --labels /path/to/labels.txt \
    --output /path/to/output.json \
    <option> --ext xml


    Tesla K20c with CUDA capability sm_35 is not compatible with the current PyTorch installation.
The current PyTorch install supports CUDA capabilities sm_37 sm_50 sm_60 sm_70 sm_75.
If you want to use the Tesla K20c GPU with PyTorch, please check the instructions at https://pytorch.org/get-started/locally/

  warnings.warn(incompatible_device_warn.format(device_name, capability, " ".join(arch_list), device_name))

