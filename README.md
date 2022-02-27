im-in.space is moving to a new server. Its name: [Lucy](https://en.wikipedia.org/wiki/Lucy_(spacecraft)).


## Progress
- [x] Get the new server
- [x] Basic configuration
- [ ] Setup new backup

Apps:

- [ ] [Mastodon](#Mastodon)
- [x] Halcyon 
- [x] Pinafore

### Mastodon

- [x] Installation of dependencies
- [x] Installation of Mastodon
- [x] Copy of our .env
- [ ] **First transfert of the attachments (in progress)**
- [ ] Stop the instance (Mastodon/Sidekiq/Streaming/Tor)
- [ ] Change DNS
- [ ] Dump the DB for transfert
- [ ] Transfert the DB to the new server
- [ ] Restore of the DB
- [ ] Start Mastodon on the new server (Mastodon/Sidekiq/Streaming/Tor)
- [ ] Rebuild of the users' timelines
- [ ] Build of the Elasticsearch index
- [ ] Transfert of possible remaining attachments in the background

<style>
ul.task-list {
  list-style: none;
  padding-left: 0;
}

.task-list-item-checkbox {
  margin-right: 10px;
}
</style>
