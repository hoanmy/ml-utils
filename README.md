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