dnl
dnl Configure script for nginx compressed build...
dnl
dnl

AC_INIT([sandgourd], [0.0.1], [zand3rs@gmail.com])

AC_PREFIX_DEFAULT([/usr/local/nginx])
AC_ARG_WITH([s3-bucket],
            AC_HELP_STRING([--with-s3-bucket], [s3 bucket]),
            AC_SUBST([S3_BUCKET], [$with_s3_bucket]),
            AC_SUBST([S3_BUCKET], []))
AC_ARG_WITH([s3-access-key],
            AC_HELP_STRING([--with-s3-access-key], [s3 access key]),
            AC_SUBST([S3_ACCESS_KEY], [$with_s3_access_key]),
            AC_SUBST([S3_ACCESS_KEY], []))
AC_ARG_WITH([s3-secret-key],
            AC_HELP_STRING([--with-s3-secret-key], [s3 secret key]),
            AC_SUBST([S3_SECRET_KEY], [$with_s3_secret_key]),
            AC_SUBST([S3_SECRET_KEY], []))

AC_CONFIG_FILES([build.sh], [chmod +x build.sh])

AC_OUTPUT([
    Makefile
])

