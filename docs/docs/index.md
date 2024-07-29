# Illegal Fishing Classification documentation!

## Description

Marine life has a significant impact on our planet, providing food, oxygen, and biodiversity. Unfortunately, 90% of the large fish are gone primarily as a result of overfishing. In addition, many major fisheries notice increases in illegal fishing, undermining the efforts to conserve and manage fish stocks. Detecting fishing activities in the ocean is a crucial step in achieving sustainability.

## Commands

The Makefile contains the central entry points for common tasks related to this project.

### Syncing data to cloud storage

* `make sync_data_up` will use `aws s3 sync` to recursively sync files in `data/` up to `s3://s3://illegal-fishing-classification//data/`.
* `make sync_data_down` will use `aws s3 sync` to recursively sync files from `s3://s3://illegal-fishing-classification//data/` to `data/`.


