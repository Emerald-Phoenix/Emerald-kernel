#
# Arch-specific CryptoAPI modules.
#

#Keep this at the top
obj-$(CONFIG_CRYPTO_FIPS) += first_file_asm.o

obj-$(CONFIG_CRYPTO_AES_ARM) += aes-arm.o
obj-$(CONFIG_CRYPTO_AES_ARM_CE) += aes-arm-ce.o
obj-$(CONFIG_CRYPTO_SHA1_ARM) += sha1-arm.o
obj-$(CONFIG_CRYPTO_SHA1_ARM_CE) += sha1-arm-ce.o
obj-$(CONFIG_CRYPTO_SHA2_ARM_CE) += sha2-arm-ce.o

aes-arm-y  := aes-armv4.o aes_glue.o
sha1-arm-y := sha1-armv4-large.o sha1_glue.o
sha1-arm-ce-y	:= sha1-ce-core.o sha1-ce-glue.o
sha2-arm-ce-y	:= sha2-ce-core.o sha2-ce-glue.o
aes-arm-ce-y	:= aes-ce-core.o aes-ce-glue.o

#Keep this at the bottom
obj-$(CONFIG_CRYPTO_FIPS) += last_file_asm.o
