mkdir cli_tmp
touch cli_tmp/je_suis_dans_tmp.txt
cd cli_tmp
mkdir in_cli_tmp
rm -rf je suis_dans_tmp.txt
rm -rf in_cli_tmp
mkdir grand_parent parent grand_frere grande_soeur ami connaissances
cd grand_frere
touch bachir
mv bachir ../ami
cd .. 
cp -r  ami parent
cd grand_frere 
rm -rf bachir
pwd
cd ~
rm -rf cli_tmp

