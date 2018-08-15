ompile step:
	 . build/envsetup.sh
	lunch full_wisky8176_tb_n-user
	make -j8



System firmware directory:
	out/target/product/wisky8176_tb_n/


Copy system firmware script:
	wisky/tools/copyimages.sh 
