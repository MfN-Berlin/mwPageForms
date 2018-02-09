# mwPageForms
A fork of mediawiki-extensions-PageForms that is compatible with MediaWiki 1.27 and Mozilla 58.

# Install
PageForms_DOWNLOAD_URL=https://github.com/MfN-Berlin/mwPageForms/archive/master.zip
curl -fSL $PageForms_DOWNLOAD_URL -o PageForms.zip \
&& unzip PageForms.zip -d extensions \
&& mv extensions/mediawiki-extensions-PageForms-REL1_27 extensions/PageForms \
&& rm PageForms.zip
