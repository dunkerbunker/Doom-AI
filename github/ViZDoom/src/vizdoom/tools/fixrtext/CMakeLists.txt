cmake_minimum_required(VERSION 3.5)

if( NOT CMAKE_CROSSCOMPILING )
	add_executable( fixrtext fixrtext.c )
	set( CROSS_EXPORTS ${CROSS_EXPORTS} fixrtext PARENT_SCOPE )
endif( NOT CMAKE_CROSSCOMPILING )
