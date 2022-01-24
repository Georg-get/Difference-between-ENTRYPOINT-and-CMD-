Основная разница между ENTRYPOINT и CMD . CMD это аргумент для ENTRYPOINT напримет : 

FROM alpine
ENTRYPOINT ["ping"]
CMD ["8.8.8.8"] 
