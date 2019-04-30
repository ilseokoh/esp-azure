set(COMPONENT_SRCS "azure_main.c"
				"prov_dev_client_ll_symmkey_sample.c"
				)
set(COMPONENT_ADD_INCLUDEDIRS ".")

register_component()

component_compile_definitions(SET_TRUSTED_CERT_IN_SAMPLES)
