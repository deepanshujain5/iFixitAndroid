Official iFixit Android App
===========================

## Version 2.0.0


## Installation

Start by cloning the repo:

    git clone https://github.com/iFixit/iFixitAndroid.git

Copy `gradle.properties.base` to `gradle.properties`. This contains all of the
values necessary to build the app in debug mode. To build the app in release
mode, update the necessary keystore information and symlink
`App/sites/{siteName}/keystore` to your keystore like so:

    ln -s /path/to/keystore App/sites/ifixit/keystore

Open the project in your IDE of choice or build it on the command line by
invoking gradle commands such as `gradle installIfixitDebug`.

## API Documentation

[iFixit API documentation](https://www.ifixit.com/api/2.0/docs)

## Contributing

This app is a native Android version of the iFixit website including:

*   Device hierarchy browsing
*   Answers and guide lists for devices
*   Guide view
*   Media manager integration: viewing and uploading of images
*   Guide lists for favorites, featured, and teardowns
*   Guide creation and editing

We have a small development team, and don't have the resources to do all of these
ourselves. We'd love help! If any of those problems looks interesting to you,
fork our code and hack away!

Got an awesome feature idea that we don't have an API to support yet? Post the
request on meta.ifixit.com and we'll add it to our to-do list.

## Licensing

>    This source code is licensed under the GPLv3.
>    Any submissions to this project must also be licensed under GPLv3.
>    The contents of this software are subject to the terms of the GNU General Public License (the "License").
>    You may not use this software except in compliance with this License.
>    You can obtain a copy of the license at [http://www.gnu.org/licenses/gpl-3.0.txt](http://www.gnu.org/licenses/gpl-3.0.txt).
>    See the License for the specific language governing permissions and limitations under the License.


## TRADEMARK NOTES

All iFixit trademarks contained herein are NOT licensed for use by any third-parties.
Their inclusion in this open source software is only for their eventual replacement if
you distribute the application.

That is, the trademarks are protected, but the code itself is under an open license. You
can use the trademarks individually, but not for any sort of distribution.

Copyright (c) 2012 iFixit

