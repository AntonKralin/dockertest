FROM redis
RUN mkdir -p /etc/redis
COPY redis.conf /etc/redis/redis.conf
VOLUME /data
EXPOSE 6379
CMD ["redis-server"]

