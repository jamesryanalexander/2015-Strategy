# 2015-Strategy
Submodule created for LCATools to help filter and analyze comments to the 2015 strategy consultation

### Files
* Datapullprocess.php - Form and processing script to pull down a day (or specifically a page's worth) of comments and process them (check what wiki the user is from, what country the IP is from ect). Stores data in database.
* displaycomments.php - Displays already processed comments and meta data and allows for filtering of same.
* downloaddata.php - Script to allow the downloading of the comments for offline analysis.
* page-strategy.php - Wrapping page to replace the normal lca page sidebar etc since those who have access to strategy tool do not all have access to the main tool system.
