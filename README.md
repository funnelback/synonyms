# Reusable synonym files / thesaurii

The `synonyms.cfg` files contained within this repository can be used with a Funnelback frontend service to provide pre-defined synonym expansions.

## Synonym files

The repository currently includes the following synonym files that can be downloaded:

* `common-names/synonyms.cfg`: includes name expansions for person first names. This can be used with any people search to provide name expansion for common first name variations.

Further `synonyms.cfg` files will be added as they become available.

The synonym files are in the v2 synonyms format which are compatible with all recent versions of Funnelback. 

## Installation instructions

1. Download the appropriate `synonyms.cfg` file

2. Log in to the Funnelback administration and change to the collection where the synonyms should be used.

3. Select _browse collection configuration files_ from the administer tab.

4. Scroll down to the profile (preview) file listing for the profile where you wish to install the synonyms.

5. Use the upload file control below the file listing for the relevant profile to upload the `synonyms.cfg` file that you downloaded. Note: if the profile has existing synonyms defined they will be overwritten. If you wish to keep existing synonyms you will need to download those and re-renter them after uploading the new `synonyms.cfg`.

6. Return to the administration interface and select _customise synonyms_ from the _customise_ tab, or edit the synonyms within the marketing dashboard. The imported synonyms should be listed. Click the _publish all_ button to apply these to your search. You can add additional synonyms to the list.