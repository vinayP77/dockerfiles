FROM almalinux:9
ENV cousre="DevOps with AWS"\
    trainer="vinay nadiu"\
    duration="140hr per month"
    #here user1 is key, someuser is default value
# ARG user1=someuser
ARG ${username:-some_user}
RUN echo "Hello ${trainer}"  > /tmp/devops.txt
CMD ["sleep", "300"] 