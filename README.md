# SVN Thumbnailer

A post commit hook for your Subversion server that will thumbnail images for use in a web-viewer,
or something like that.

## Requirements

 - A subversion server
 - Imagemagick (any version) or compatible

## Installation

Create `/var/svn/thumbs/' and chown to the SVN server user.

Put in `/var/svn/hooks` or equivalent. 

## Notes

Will only thumbnail new commits, won't process existing content.
