# Udagram Image Filtering Microservice

This is the second assignment for the [Udacity Cloud Developer Nanodegree course](https://www.udacity.com/course/cloud-developer-nanodegree--nd9990).

It is a Node-Express application which runs a simple script to process images, and is deployed using AWS Elastic Beanstalk.

### Usage
**Base url:** http://udagram-image-filter-ofa-dev.us-east-1.elasticbeanstalk.com
#### filtering an image
| Path | Parameter | Description |
| :--- | :--- | :--- |
| filteredimage | `image_url` | **Required**. The image url to filter |

**Example:** http://udagram-image-filter-ofa-dev.us-east-1.elasticbeanstalk.com/filteredimage?image_url=https://www.gstatic.com/webp/gallery3/1.png

Note: _All API requests __require__ authorization headers_ (click [here](http://udagram-image-filter-ofa-dev.us-east-1.elasticbeanstalk.com/token) to generate a token).

*Postman collection file is [here](https://github.com/omerfarukakdag/udagram-image-filter/blob/master/cloud-cdnd-c2-final.postman_collection.json).*
