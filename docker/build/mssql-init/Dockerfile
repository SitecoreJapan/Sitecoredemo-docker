# escape=`

ARG BASE_IMAGE
ARG SPE_IMAGE
ARG HEADLESS_SERVICES_IMAGE

FROM ${SPE_IMAGE} as spe
FROM ${HEADLESS_SERVICES_IMAGE} as headless_services
FROM ${BASE_IMAGE}

# Add Headless module
COPY --from=headless_services C:\module\db C:\jss_data

COPY --from=spe C:\module\db C:\resources\spe