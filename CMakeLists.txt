cmake_minimum_required(VERSION 3.25)

find_package(cmake-pear REQUIRED PATHS node_modules/cmake-pear)

project(pear_runtime_appling C)

add_pear_appling(
  pear_runtime_appling
  KEY pear-runtime
  NAME "Pear Runtime"
  VERSION 1.0.0
  AUTHOR Holepunch
  DESCRIPTION "Pear Runtime"

  MACOS_IDENTIFIER com.pears.docs
  MACOS_CATEGORY public.app-category.developer-tools
  MACOS_SIGNING_IDENTITY "09590CDE64938DA62FA174A68C240D346B05EF49"

  WINDOWS_SIGNING_SUBJECT "CN=Holepunch Inc, O=Holepunch Inc, S=British Virgin Islands (the), C=GB, OID.2.5.4.15=Private Organization, OID.1.3.6.1.4.1.311.60.2.1.2=British Virgin Islands (the), OID.1.3.6.1.4.1.311.60.2.1.3=GB, SERIALNUMBER=2009762"
  WINDOWS_SIGNING_THUMBPRINT "E890AF027C9C83F7427BCEEBE7AC533579DFE549"

  LINUX_CATEGORY Development
)
