$$
```python
File: trkwebctrl
Build ID: eb53bae02d1c0cebf181d6aa585422bdebdd5c7b
Type: inuse_space
Time: Jul 11, 2023 at 12:49pm (MSK)
Showing nodes accounting for 702.15MB, 95.43% of 735.78MB total
Dropped 124 nodes (cum <= 3.68MB)
      flat  flat%   sum%        cum   cum%
  258.74MB 35.17% 35.17%   258.74MB 35.17%  github.com/allegro/bigcache/v3/queue.NewBytesQueue (inline)
  249.45MB 33.90% 69.07%   508.19MB 69.07%  github.com/allegro/bigcache/v3.initNewShard
  134.61MB 18.30% 87.36%   134.61MB 18.30%  github.com/segmentio/encoding/json.decoder.decodeBytes
   38.62MB  5.25% 92.61%    38.62MB  5.25%  github.com/syndtr/goleveldb/leveldb/util.(*BufferPool).Get
    6.77MB  0.92% 93.53%     6.77MB  0.92%  marketingPlatform/ak/rmq/publisher.NewSession
    5.08MB  0.69% 94.22%    48.38MB  6.58%  marketingPlatform/ak/proc/tracking/trkwebctrl/trackingwebcontrol.(*TrackingWebControl).getPopupContent
    4.39MB   0.6% 94.82%     4.39MB   0.6%  runtime/pprof.(*profMap).lookup
       4MB  0.54% 95.36%        4MB  0.54%  github.com/syndtr/goleveldb/leveldb/memdb.New
    0.50MB 0.068% 95.43%   528.93MB 71.89%  runtime.main
         0     0% 95.43%   508.19MB 69.07%  github.com/allegro/bigcache/v3.New (inline)
         0     0% 95.43%   508.19MB 69.07%  github.com/allegro/bigcache/v3.newBigCache
         0     0% 95.43%    50.43MB  6.85%  github.com/gin-gonic/gin.(*Context).Next (inline)
         0     0% 95.43%    40.95MB  5.57%  github.com/gin-gonic/gin.(*Engine).ServeHTTP
         0     0% 95.43%    50.43MB  6.85%  github.com/gin-gonic/gin.(*Engine).handleHTTPRequest
         0     0% 95.43%    50.43MB  6.85%  github.com/gin-gonic/gin.CustomRecoveryWithWriter.func1
         0     0% 95.43%   135.11MB 18.36%  github.com/segmentio/encoding/json.Parse
         0     0% 95.43%   135.11MB 18.36%  github.com/segmentio/encoding/json.Unmarshal
         0     0% 95.43%   134.61MB 18.30%  github.com/segmentio/encoding/json.constructMapDecodeFunc.func1
         0     0% 95.43%   134.61MB 18.30%  github.com/segmentio/encoding/json.constructStructDecodeFunc.func1
         0     0% 95.43%   134.61MB 18.30%  github.com/segmentio/encoding/json.decoder.decodeMap
         0     0% 95.43%   134.61MB 18.30%  github.com/segmentio/encoding/json.decoder.decodeStruct
         0     0% 95.43%   135.11MB 18.36%  github.com/smallnest/rpcx/client.(*Client).input
         0     0% 95.43%    30.35MB  4.12%  github.com/syndtr/goleveldb/leveldb.(*DB).Get
         0     0% 95.43%     4.69MB  0.64%  github.com/syndtr/goleveldb/leveldb.(*DB).Write
         0     0% 95.43%        4MB  0.54%  github.com/syndtr/goleveldb/leveldb.(*DB).flush
         0     0% 95.43%        4MB  0.54%  github.com/syndtr/goleveldb/leveldb.(*DB).flush.func1
         0     0% 95.43%    30.35MB  4.12%  github.com/syndtr/goleveldb/leveldb.(*DB).get
         0     0% 95.43%        4MB  0.54%  github.com/syndtr/goleveldb/leveldb.(*DB).mpoolGet
         0     0% 95.43%        4MB  0.54%  github.com/syndtr/goleveldb/leveldb.(*DB).newMem
         0     0% 95.43%        4MB  0.54%  github.com/syndtr/goleveldb/leveldb.(*DB).rotateMem
         0     0% 95.43%     4.69MB  0.64%  github.com/syndtr/goleveldb/leveldb.(*DB).writeLocked
         0     0% 95.43%     8.27MB  1.12%  github.com/syndtr/goleveldb/leveldb.(*dbIter).Seek
         0     0% 95.43%     8.27MB  1.12%  github.com/syndtr/goleveldb/leveldb.(*tFilesArrayIndexer).Get
         0     0% 95.43%    30.35MB  4.12%  github.com/syndtr/goleveldb/leveldb.(*tOps).find
         0     0% 95.43%     8.27MB  1.12%  github.com/syndtr/goleveldb/leveldb.(*tOps).newIterator
         0     0% 95.43%    30.35MB  4.12%  github.com/syndtr/goleveldb/leveldb.(*version).get
         0     0% 95.43%    30.35MB  4.12%  github.com/syndtr/goleveldb/leveldb.(*version).get.func1
         0     0% 95.43%    30.35MB  4.12%  github.com/syndtr/goleveldb/leveldb.(*version).walkOverlapping
         0     0% 95.43%    30.35MB  4.12%  github.com/syndtr/goleveldb/leveldb/cache.(*Cache).Get
         0     0% 95.43%    30.35MB  4.12%  github.com/syndtr/goleveldb/leveldb/cache.(*NamespaceGetter).Get (inline)
         0     0% 95.43%     8.27MB  1.12%  github.com/syndtr/goleveldb/leveldb/iterator.(*arrayIteratorIndexer).Get
         0     0% 95.43%     8.27MB  1.12%  github.com/syndtr/goleveldb/leveldb/iterator.(*indexedIterator).Seek
         0     0% 95.43%     8.27MB  1.12%  github.com/syndtr/goleveldb/leveldb/iterator.(*indexedIterator).setData
         0     0% 95.43%     8.27MB  1.12%  github.com/syndtr/goleveldb/leveldb/iterator.(*mergedIterator).Seek
         0     0% 95.43%    30.35MB  4.12%  github.com/syndtr/goleveldb/leveldb/table.(*Reader).Find (inline)
         0     0% 95.43%     8.27MB  1.12%  github.com/syndtr/goleveldb/leveldb/table.(*Reader).NewIterator
         0     0% 95.43%    30.35MB  4.12%  github.com/syndtr/goleveldb/leveldb/table.(*Reader).find
         0     0% 95.43%     4.60MB  0.63%  github.com/syndtr/goleveldb/leveldb/table.(*Reader).getFilterBlock
         0     0% 95.43%    34.01MB  4.62%  github.com/syndtr/goleveldb/leveldb/table.(*Reader).getIndexBlock
         0     0% 95.43%    34.01MB  4.62%  github.com/syndtr/goleveldb/leveldb/table.(*Reader).readBlock
         0     0% 95.43%    34.01MB  4.62%  github.com/syndtr/goleveldb/leveldb/table.(*Reader).readBlockCached
         0     0% 95.43%    25.75MB  3.50%  github.com/syndtr/goleveldb/leveldb/table.(*Reader).readBlockCached.func1
         0     0% 95.43%     4.60MB  0.63%  github.com/syndtr/goleveldb/leveldb/table.(*Reader).readFilterBlock
         0     0% 95.43%     4.60MB  0.63%  github.com/syndtr/goleveldb/leveldb/table.(*Reader).readFilterBlockCached
         0     0% 95.43%     4.60MB  0.63%  github.com/syndtr/goleveldb/leveldb/table.(*Reader).readFilterBlockCached.func1
         0     0% 95.43%    38.62MB  5.25%  github.com/syndtr/goleveldb/leveldb/table.(*Reader).readRawBlock
         0     0% 95.43%    20.37MB  2.77%  lab.altkraft.com/altkraft/ledisdb/ledis.(*DB).HGet
         0     0% 95.43%     8.27MB  1.12%  lab.altkraft.com/altkraft/ledisdb/ledis.(*DB).HGetAll
         0     0% 95.43%    13.98MB  1.90%  lab.altkraft.com/altkraft/ledisdb/ledis.(*DB).HSet
         0     0% 95.43%     5.14MB   0.7%  lab.altkraft.com/altkraft/ledisdb/ledis.(*DB).hIncrSize
         0     0% 95.43%     9.98MB  1.36%  lab.altkraft.com/altkraft/ledisdb/ledis.(*DB).hSetItem
         0     0% 95.43%     4.69MB  0.64%  lab.altkraft.com/altkraft/ledisdb/ledis.(*Ledis).handleCommit
         0     0% 95.43%     4.69MB  0.64%  lab.altkraft.com/altkraft/ledisdb/ledis.(*batch).Commit
         0     0% 95.43%    30.35MB  4.12%  lab.altkraft.com/altkraft/ledisdb/store.(*DB).Get
         0     0% 95.43%     8.27MB  1.12%  lab.altkraft.com/altkraft/ledisdb/store.(*DB).RangeLimitIterator
         0     0% 95.43%     8.27MB  1.12%  lab.altkraft.com/altkraft/ledisdb/store.(*Iterator).Seek (inline)
         0     0% 95.43%     4.69MB  0.64%  lab.altkraft.com/altkraft/ledisdb/store.(*WriteBatch).Commit
         0     0% 95.43%     8.27MB  1.12%  lab.altkraft.com/altkraft/ledisdb/store.NewRangeLimitIterator (inline)
         0     0% 95.43%     8.27MB  1.12%  lab.altkraft.com/altkraft/ledisdb/store.rangeLimitIterator
         0     0% 95.43%    30.35MB  4.12%  lab.altkraft.com/altkraft/ledisdb/store/goleveldb.(*DB).Get
         0     0% 95.43%     8.27MB  1.12%  lab.altkraft.com/altkraft/ledisdb/store/goleveldb.(*Iterator).Seek
         0     0% 95.43%     4.69MB  0.64%  lab.altkraft.com/altkraft/ledisdb/store/goleveldb.(*WriteBatch).Commit
         0     0% 95.43%   519.64MB 70.62%  main.main
         0     0% 95.43%   508.19MB 69.07%  marketingPlatform/ak/control/filecache.NewFileCache
         0     0% 95.43%   519.64MB 70.62%  marketingPlatform/ak/daemonize.(*Daemonizer).Daemonize
         0     0% 95.43%   135.11MB 18.36%  marketingPlatform/ak/proc/procrpc/rpccodecs.(*SegmentioCodec).Decode
         0     0% 95.43%     9.78MB  1.33%  marketingPlatform/ak/proc/tracking/trkwebctrl/trackingwebcontrol.(*TrackingWebControl).Init
         0     0% 95.43%   509.86MB 69.29%  marketingPlatform/ak/proc/tracking/trkwebctrl/trackingwebcontrol.(*TrackingWebControl).Run
         0     0% 95.43%    48.88MB  6.64%  marketingPlatform/ak/proc/tracking/trkwebctrl/trackingwebcontrol.(*TrackingWebControl).popupContent
         0     0% 95.43%    50.43MB  6.85%  marketingPlatform/ak/proc/tracking/trkwebctrl/trackingwebcontrol.syncReq.func2
         0     0% 95.43%   508.19MB 69.07%  marketingPlatform/ak/proc/tracking/trkwebctrl/trackingwebcontrol/services/enrichment_service.NewEnrichmentService
         0     0% 95.43%    43.30MB  5.89%  marketingPlatform/ak/proc/tracking/trkwebctrl/trackingwebcontrol/services/matching_service.(*MatchingService).RestoreAcidProccesing
         0     0% 95.43%    20.37MB  2.77%  marketingPlatform/ak/proc/tracking/trkwebctrl/trackingwebcontrol/services/matching_service.(*MatchingService).getAcidByClientFPrint
         0     0% 95.43%     8.27MB  1.12%  marketingPlatform/ak/proc/tracking/trkwebctrl/trackingwebcontrol/services/matching_service.(*MatchingService).getAcidByServerFPrint
         0     0% 95.43%    20.37MB  2.77%  marketingPlatform/ak/proc/tracking/trkwebctrl/trackingwebcontrol/services/matching_service.(*MatchingService).getAcidFromCache
         0     0% 95.43%     8.27MB  1.12%  marketingPlatform/ak/proc/tracking/trkwebctrl/trackingwebcontrol/services/matching_service.(*MatchingService).getAcidFromCacheByServerFP
         0     0% 95.43%    14.67MB  1.99%  marketingPlatform/ak/proc/tracking/trkwebctrl/trackingwebcontrol/services/matching_service.(*MatchingService).overwriteAcid
         0     0% 95.43%    14.67MB  1.99%  marketingPlatform/ak/proc/tracking/trkwebctrl/trackingwebcontrol/services/matching_service.(*MatchingService).setAcidToCache
         0     0% 95.43%     6.77MB  0.92%  marketingPlatform/ak/rmq/publisher.NewPublisher (inline)
         0     0% 95.43%     6.77MB  0.92%  marketingPlatform/ak/rmq/publisher.configurePublisher
         0     0% 95.43%    50.43MB  6.85%  marketingPlatform/ak/tools/ginlogger.middleware.func1
         0     0% 95.43%    16.82MB  2.29%  net/http.(*conn).serve
         0     0% 95.43%    11.80MB  1.60%  net/http.serverHandler.ServeHTTP
         0     0% 95.43%     8.79MB  1.19%  runtime.doInit
         0     0% 95.43%     4.39MB   0.6%  runtime/pprof.(*profileBuilder).addCPUData
         0     0% 95.43%     4.39MB   0.6%  runtime/pprof.profileWriter
```
$$