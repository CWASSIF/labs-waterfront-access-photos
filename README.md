# labs-waterfront-access-photos
Photos of Publicly Accessible Waterfront Spaces (PAWS), consumed by the [NYC Waterfront Access Map](https://github.com/NYCPlanning/labs-waterfront-access).

## Organization
This repo contains one directory for each `paws_id`. Each directory can contain one or more images (jpg or png), image filenames are not important.

## Image Size and Orientation
All images should be in landscape orientation, with a preferred width of 1500 pixels

## Consumption
A simple call to the github API will list a folder's contents:

`https://api.github.com/repos/nycplanning/labs-waterfront-access-photos/contents/1030001`

The resulting array of JSON objects includes a `download_url` property, which can be used to build out an `img` tag
