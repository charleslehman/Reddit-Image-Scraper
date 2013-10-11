Reddit Image Scraper: A perl script to download images hosted on 
the imgur.com hosting service linked from a subreddit at reddit.com
Copyright (C) 2013 Joshua Hull

[![endorse](http://api.coderwall.com/joshua-hull/endorsecount.png)](http://coderwall.com/joshua-hull)

The author will happily accept any donations of Bitcoins at the address shown
below. A QR Code has been provided for convenience:

Address: 1PF95G1gpdsKDwEbVmUwbEy89azf7amT2R

QR Code:

![QR Code](http://github.com/joshua-hull/Reddit-Image-Scraper/raw/master/qrcode.jpg "Bitcoin QR Code")

This program is free software: you can redistribute it and/or modify 
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.

Usage: ./Reddit_Image_Scraper [-l limit] [-u] [-q] subbreddit1|username1|query1 [subbreddit2|username2|query2 ...]

Reddit Image Scraper is a perl script designed to read in one or more
subreddits and download all the images in it that are hosted on the
imgur.com image hosting site. Be aware that this script can chew 
through bandwidth quickly, especially if given a large list of
subreddits. Please be courteous of the bandwidth of both reddit.com
and imgur.com. Let's keep these two free resouces just that: free.

Prune.sh:

Usage: ./Prune.sh [min # of photos]
		or
       ./Prune.sh -1

Prune.sh is a shell script to help maintain a collection of directories
created from Reddit_Image_Scrpaer. Running Prune.sh with a positive number 
will delete any directory with less than that number of photos. Running it
with a -1 will list all the directorys and the number of photos in them.

You can find more information on installing Perl on your computer system at [Perl.org](http://www.perl.org/get.html "Perl.org")

You can find information on using Perl at [Perl.org](http://www.perl.org/get.html "Perl.org")
