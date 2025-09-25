FROM alpine:3.19
#RUN apk --no-cache add curl
RUN apk --no-cache add curl

#COPY --chmod=755 ./generator.sh .
COPY --chmod=755 ./generator.sh .

#CMD [ "./generator.sh" ]
CMD ["sh","./generator.sh"]