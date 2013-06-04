brain_data
==========

Sample data for brain registration

* **brain_data**:           contains the atlas images and sample subject images
 * **Allen**:         atlas images. See config.atlas_menu for a list of atlas datasets.
      * \<atlas_id\>: contains all raw images in the atlas
      * \<atlas_id\>_atlas: contains all annotated images
      * \<atlas_id\>_warp: contains images that are warped into alignment, using transforms obtained from web API.
      * \<atlas_id\>.p: the pickle file containing indexing information about this atlas
 * **Section**:       subject images. Each folder is named with \<subject_id\> and contains segmented raw section images in the subject stack.
