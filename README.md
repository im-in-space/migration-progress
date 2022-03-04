im-in.space is moving to a new server. Its name: [Lucy](https://en.wikipedia.org/wiki/Lucy_(spacecraft)).


## Progress
- [x] Get the new server
- [x] Basic configuration
- [x] Setup new backup

Apps:

- [x] Mastodon
- [x] Halcyon 
- [x] Pinafore

### Mastodon

- [x] Installation of dependencies
- [x] Installation of Mastodon
- [x] Copy of our .env
- [x] First transfert of the attachments
- [x] Stop the instance on the old server (Mastodon/Sidekiq/Streaming/Tor)
- [x] Change DNS
- [x] Dump the DB/Redis for transfert
- [x] Transfert the DB/Redis to the new server
- [x] Restore of the DB/Redis
- [x] Start the install on the new server (Mastodon/Sidekiq/Streaming/Tor)
- [x] Rebuild of the users' timelines
- [x] Build of the Elasticsearch index
- [x] Transfert of possible remaining attachments in the background

<style>
ul.task-list {
  list-style: none;
  padding-left: 0;
}

.task-list-item-checkbox {
  margin-right: 10px;
}
</style>
