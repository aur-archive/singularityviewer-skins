# Maintainer: GordonGR <gordongr@freemail.gr>

pkgname=singularityviewer-skins
pkgver=20130413
pkgrel=1
pkgdesc="Extra skins for Singularity (and any other V1-type viewers) for Second Life (secondlife) and OpenSim (opensimulator)."
url="http://sites.google.com/site/seletnomcreations/telechargements/xtra-skins"
license=('GPL')
depends=('singularityviewer')
arch=('any')
source=("http://sites.google.com/site/seletnomcreations/telechargements/xtra-skins/ApolloSkin.zip"
"http://sites.google.com/site/seletnomcreations/telechargements/xtra-skins/DarkCatalanSkin.zip"
"http://sites.google.com/site/seletnomcreations/telechargements/xtra-skins/FrenchTouchSkin.zip"
"http://sites.google.com/site/seletnomcreations/telechargements/xtra-skins/ItaliaSkin.zip"
"http://sites.google.com/site/seletnomcreations/telechargements/xtra-skins/NewSilverSkin.zip"
"http://sites.google.com/site/seletnomcreations/telechargements/xtra-skins/OrangeLifeSkin.zip"
"http://sites.google.com/site/seletnomcreations/telechargements/xtra-skins/SecondLoveSkin.zip"
"http://sites.google.com/site/seletnomcreations/telechargements/xtra-skins/SnowWhite%20Skin.zip"
"http://sites.google.com/site/seletnomcreations/telechargements/xtra-skins/St%20Patrick%20Skin.zip"
"http://sites.google.com/site/seletnomcreations/telechargements/xtra-skins/WhiteGreenLifeSkin.zip"
"http://sites.google.com/site/seletnomcreations/telechargements/xtra-skins/kirstenLite2Skin.zip"
)

md5sums=('6cbdeb82fd2226ee78800ccc2b2797d2'
         '26030569863b14060188424a950bdf46'
         '0abbc2f6a3fda1d6223a108a0ad7f3b5'
         'dc3645120ac6205caafc701738cad645'
         'b24fec6d48489687955f1c871f03d57e'
         'ec4fcf95ccc5d03103938576c65ba6b2'
         '5eb5087889581057e12c738775439e6b'
         '45796905660f865f898efb54cfe81cf5'
         '977f0a4139830acddc5935edde29b258'
         '30db42a43b9015b3f8919aedbcfeb702'
         '03c59d3847cecbc4fd6ed75d70b9f5f1')

        
package() {
  cd $srcdir
  rm *.png
  rm *.zip
  # Install needed files and directories
  mkdir -p $pkgdir/opt/singularityviewer/skins
  cp -R * $pkgdir/opt/singularityviewer/skins/
}
