ROOT_ADD_GTEST(testStatusBitsChecker testStatusBitsChecker.cxx LIBRARIES Core)
ROOT_ADD_GTEST(testHashRecursiveRemove testHashRecursiveRemove.cxx LIBRARIES Core)
ROOT_ADD_GTEST(testTClass testTClass.cxx LIBRARIES Core)
<<<<<<< HEAD
configure_file(stlDictCheck.h . COPYONLY)
=======
ROOT_ADD_GTEST(testTEnum testTEnum.cxx LIBRARIES Core)
configure_file(stlDictCheck.h . COPYONLY)
configure_file(stlDictCheckAux.h . COPYONLY)
>>>>>>> 3421b34... [meta][TCling] Add TEnum::IsScopedEnum(), GetUnderlyingType() (ROOT-6988):
