FROM "amazonlinux:2022"

RUN curl https://raw.githubusercontent.com/microsoft/vscode-dev-containers/main/script-library/common-redhat.sh -o /tmp/common-redhat.sh \
    && cat /tmp/common-redhat.sh | grep -v redhat-lsb-core > /tmp/common-redhat-edit.sh \
    && bash /tmp/common-redhat-edit.sh