================================================================================================
================================================================================================
vsenseVVDB2 - Volumetric Video Compression Database #2
==========================================================================

This database includes Volumetric Video Sequences compressed using three
  different state-of-the-art compression tools: (i) Draco for textured 
  meshes, (ii) G-PCC (also called as TMC13), and (iii) V-PCC (also called
  as TMC2) for point clouds. The database provides the reference sequences
  for four original volumetric videos (in both mesh and point cloud 
  format), their compressed bitstreams, reconstructed volumetric videos,
  and the corresponding subjective quality scores for these compressed 
  video sequences. The details are presented in [1]. If you use this 
  database in your research, please kindly cite [1] in your publications:

[1] E. Zerman, C. Ozcinar, P. Gao, A. Smolic. "Textured Mesh vs Coloured 
    Point Cloud: A Subjective Study for Volumetric Video Compression." 
    Twelfth International Conference on Quality of Multimedia Experience 
    (QoMEX), Athlone, Ireland, May 2020.

=====================================
V-SENSE, SCSS, Trinity College Dublin
Emin Zerman
emin.zerman@tcd.ie
=====================================

CONTENTS
========

+ 'references'
      This folder contains the reference uncompressed volumetric video
      sequences in two different formats: (i) textured mesh and 
      (ii) point clouds. Textured mesh folders include three files (obj, 
      mtl, and jpg) for each 3D model whereas point clouds include only 
      a single file per 3D model. The provided volumetric video folders
      are as follows:
       + AxeGuy_obj
       + AxeGuy_ply_400K
       + LubnaFriends_obj
       + LubnaFriends_ply_400K
       + Matis_obj
       + Matis_ply_400K
       + Rafa2_obj
       + Rafa2_ply_400K

+ 'distorted_bitstreams'
      This folder contains the compressed bitstreams for four different
      cases, as described in the paper: (i) Draco+JPEG, (ii) G-PCC RAHT,
      (iii) V-PCC All-Intra, and (iv) V-PCC Random-Access. Additionally,
      a readme file is provided to point out the links for the 
      compression algorithms used.

+ 'distorted_reconstructed'
      This folder contains the reconstructed volumetric videos for all
      88 cases regarding the four original contents in both textured 
      mesh and point cloud formats. Textured mesh folders include three
      files (obj, mtl, and jpg) for each 3D model whereas point clouds 
      include only a single file per 3D model.

+ 'scores' 
      This folder contains the subjective quality scores collected from
      23 volunteered participants, as described in the paper. Please
      read the readme file in the 'scores' folder for detailed 
      information regarding the folder's contents.

+ 'commandsFor8i'
      As we do not have the rights to redistribute the 8i point cloud
      database, we provide the commands we used for the compression and
      decoding of 8i sequences using G-PCC and V-PCC. The 8i sequences
      can be downloaded from its original source and can be replicated
      using these commands.

================================================================================================
================================================================================================