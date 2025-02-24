cmake_minimum_required(VERSION 3.25)

find_package(cmake-pear REQUIRED PATHS node_modules/cmake-pear)

project(pear_appling C)

add_pear_appling(
  pear_appling
  KEY pear-runtime
  NAME "Pear Runtime"
  VERSION 1.0.0
  AUTHOR Holepunch
  DESCRIPTION "Pear Runtime"

  MACOS_IDENTIFIER <namespace>
  MACOS_CATEGORY <category>
  MACOS_SIGNING_IDENTITY "<id>"

  WINDOWS_SIGNING_SUBJECT "<string>"
  WINDOWS_SIGNING_THUMBPRINT <sha1>

  LINUX_CATEGORY <category>
)
