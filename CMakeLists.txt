cmake_minimum_required(VERSION 2.8.3)
project(twitter_bootstrap)

find_package(catkin REQUIRED)

catkin_package()

# the '.' is needed to resolve the symlink
install(DIRECTORY bootstrap/.
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}/bootstrap)
                                                                                                                                                       
