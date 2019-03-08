{
  "_nodes" : {
    "total" : 7,
    "successful" : 7,
    "failed" : 0
  },
  "cluster_name" : "myapp-cluster",
  "nodes" : {
    "f492qWFDQyG8fkxNwf9mfQ" : {
      "timestamp" : 1552076357462,
      "name" : "ip-10-200-180-64.kdc.capitalone.com",
      "transport_address" : "10.200.180.64:9300",
      "host" : "10.200.180.64",
      "ip" : "10.200.180.64:9300",
      "roles" : [
        "master",
        "data",
        "ingest"
      ],
      "attributes" : {
        "aws_availability_zone" : "us-east-1c",
        "ml.machine_memory" : "65842671616",
        "ml.max_open_jobs" : "20",
        "xpack.installed" : "true",
        "box_type" : "hot",
        "ml.enabled" : "true"
      },
      "indices" : {
        "docs" : {
          "count" : 4983880,
          "deleted" : 401720
        },
        "store" : {
          "size_in_bytes" : 39213158849
        },
        "indexing" : {
          "index_total" : 154512,
          "index_time_in_millis" : 308666,
          "index_current" : 0,
          "index_failed" : 0,
          "delete_total" : 0,
          "delete_time_in_millis" : 0,
          "delete_current" : 0,
          "noop_update_total" : 769,
          "is_throttled" : false,
          "throttle_time_in_millis" : 0
        },
        "get" : {
          "total" : 75314,
          "time_in_millis" : 13194,
          "exists_total" : 34429,
          "exists_time_in_millis" : 6484,
          "missing_total" : 40885,
          "missing_time_in_millis" : 6710,
          "current" : 0
        },
        "search" : {
          "open_contexts" : 1,
          "query_total" : 3538760,
          "query_time_in_millis" : 616736,
          "query_current" : 0,
          "fetch_total" : 124811,
          "fetch_time_in_millis" : 844042,
          "fetch_current" : 0,
          "scroll_total" : 364,
          "scroll_time_in_millis" : 47810427,
          "scroll_current" : 1,
          "suggest_total" : 0,
          "suggest_time_in_millis" : 0,
          "suggest_current" : 0
        },
        "merges" : {
          "current" : 0,
          "current_docs" : 0,
          "current_size_in_bytes" : 0,
          "total" : 11149,
          "total_time_in_millis" : 1263733,
          "total_docs" : 19252984,
          "total_size_in_bytes" : 25749547402,
          "total_stopped_time_in_millis" : 0,
          "total_throttled_time_in_millis" : 19542,
          "total_auto_throttle_in_bytes" : 1247860586
        },
        "refresh" : {
          "total" : 110817,
          "total_time_in_millis" : 2478167,
          "listeners" : 0
        },
        "flush" : {
          "total" : 507,
          "periodic" : 0,
          "total_time_in_millis" : 9191
        },
        "warmer" : {
          "current" : 0,
          "total" : 109724,
          "total_time_in_millis" : 5097
        },
        "query_cache" : {
          "memory_size_in_bytes" : 36858038,
          "total_count" : 5794865,
          "hit_count" : 314299,
          "miss_count" : 5480566,
          "cache_size" : 18463,
          "cache_count" : 18468,
          "evictions" : 5
        },
        "fielddata" : {
          "memory_size_in_bytes" : 40489640,
          "evictions" : 0
        },
        "completion" : {
          "size_in_bytes" : 0
        },
        "segments" : {
          "count" : 622,
          "memory_in_bytes" : 76509700,
          "terms_memory_in_bytes" : 63584848,
          "stored_fields_memory_in_bytes" : 7465296,
          "term_vectors_memory_in_bytes" : 0,
          "norms_memory_in_bytes" : 2664896,
          "points_memory_in_bytes" : 587932,
          "doc_values_memory_in_bytes" : 2206728,
          "index_writer_memory_in_bytes" : 1719044,
          "version_map_memory_in_bytes" : 174,
          "fixed_bit_set_memory_in_bytes" : 0,
          "max_unsafe_auto_id_timestamp" : 1546894432245,
          "file_sizes" : { }
        },
        "translog" : {
          "operations" : 43006,
          "size_in_bytes" : 284838754,
          "uncommitted_operations" : 41951,
          "uncommitted_size_in_bytes" : 275687368,
          "earliest_last_modified_age" : 0
        },
        "request_cache" : {
          "memory_size_in_bytes" : 41293902,
          "evictions" : 0,
          "hit_count" : 91410,
          "miss_count" : 68443
        },
        "recovery" : {
          "current_as_source" : 0,
          "current_as_target" : 0,
          "throttle_time_in_millis" : 1579635
        }
      },
      "os" : {
        "timestamp" : 1552076357548,
        "cpu" : {
          "percent" : 1,
          "load_average" : {
            "1m" : 0.06,
            "5m" : 0.06,
            "15m" : 0.06
          }
        },
        "mem" : {
          "total_in_bytes" : 65842671616,
          "free_in_bytes" : 526041088,
          "used_in_bytes" : 65316630528,
          "free_percent" : 1,
          "used_percent" : 99
        },
        "swap" : {
          "total_in_bytes" : 0,
          "free_in_bytes" : 0,
          "used_in_bytes" : 0
        },
        "cgroup" : {
          "cpuacct" : {
            "control_group" : "/",
            "usage_nanos" : 34086031180588
          },
          "cpu" : {
            "control_group" : "/",
            "cfs_period_micros" : 100000,
            "cfs_quota_micros" : -1,
            "stat" : {
              "number_of_elapsed_periods" : 0,
              "number_of_times_throttled" : 0,
              "time_throttled_nanos" : 0
            }
          },
          "memory" : {
            "control_group" : "/system.slice/elasticsearch.service",
            "limit_in_bytes" : "9223372036854771712",
            "usage_in_bytes" : "28727943168"
          }
        }
      },
      "process" : {
        "timestamp" : 1552076357549,
        "open_file_descriptors" : 901,
        "max_file_descriptors" : 65536,
        "cpu" : {
          "percent" : 1,
          "total_in_millis" : 15815050
        },
        "mem" : {
          "total_virtual_in_bytes" : 82724851712
        }
      },
      "jvm" : {
        "timestamp" : 1552076357549,
        "uptime_in_millis" : 180120294,
        "mem" : {
          "heap_used_in_bytes" : 7489092496,
          "heap_used_percent" : 23,
          "heap_committed_in_bytes" : 32098877440,
          "heap_max_in_bytes" : 32098877440,
          "non_heap_used_in_bytes" : 197223592,
          "non_heap_committed_in_bytes" : 208056320,
          "pools" : {
            "young" : {
              "used_in_bytes" : 687854400,
              "max_in_bytes" : 907345920,
              "peak_used_in_bytes" : 907345920,
              "peak_max_in_bytes" : 907345920
            },
            "survivor" : {
              "used_in_bytes" : 35804600,
              "max_in_bytes" : 113377280,
              "peak_used_in_bytes" : 113377280,
              "peak_max_in_bytes" : 113377280
            },
            "old" : {
              "used_in_bytes" : 6765433496,
              "max_in_bytes" : 31078154240,
              "peak_used_in_bytes" : 6765433496,
              "peak_max_in_bytes" : 31078154240
            }
          }
        },
        "threads" : {
          "count" : 177,
          "peak_count" : 181
        },
        "gc" : {
          "collectors" : {
            "young" : {
              "collection_count" : 19105,
              "collection_time_in_millis" : 692798
            },
            "old" : {
              "collection_count" : 2,
              "collection_time_in_millis" : 94
            }
          }
        },
        "buffer_pools" : {
          "direct" : {
            "count" : 199,
            "used_in_bytes" : 541519897,
            "total_capacity_in_bytes" : 541519896
          },
          "mapped" : {
            "count" : 1250,
            "used_in_bytes" : 38933531994,
            "total_capacity_in_bytes" : 38933531994
          }
        },
        "classes" : {
          "current_loaded_count" : 19365,
          "total_loaded_count" : 19365,
          "total_unloaded_count" : 0
        }
      },
      "thread_pool" : {
        "analyze" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "fetch_shard_started" : {
          "threads" : 1,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 5,
          "completed" : 131
        },
        "fetch_shard_store" : {
          "threads" : 1,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 14,
          "completed" : 131
        },
        "flush" : {
          "threads" : 1,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 5,
          "completed" : 1001
        },
        "force_merge" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "generic" : {
          "threads" : 7,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 7,
          "completed" : 771550
        },
        "get" : {
          "threads" : 16,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 16,
          "completed" : 37
        },
        "index" : {
          "threads" : 16,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 16,
          "completed" : 803
        },
        "listener" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "management" : {
          "threads" : 3,
          "queue" : 0,
          "active" : 1,
          "rejected" : 0,
          "largest" : 3,
          "completed" : 447066
        },
        "ml_autodetect" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "ml_datafeed" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "ml_utility" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "refresh" : {
          "threads" : 8,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 8,
          "completed" : 5006758
        },
        "rollup_indexing" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "search" : {
          "threads" : 25,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 25,
          "completed" : 3663636
        },
        "security-token-key" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "snapshot" : {
          "threads" : 1,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 5,
          "completed" : 58
        },
        "warmer" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "watcher" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "write" : {
          "threads" : 16,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 16,
          "completed" : 152198
        }
      },
      "fs" : {
        "timestamp" : 1552076357550,
        "total" : {
          "total_in_bytes" : 1056755048448,
          "free_in_bytes" : 1017163517952,
          "available_in_bytes" : 963459649536
        },
        "data" : [
          {
            "path" : "/opt/mount/var/data/myapp/elasticsearch/nodes/0",
            "mount" : "/opt/mount (/dev/nvme1n1)",
            "type" : "ext4",
            "total_in_bytes" : 1056755048448,
            "free_in_bytes" : 1017163517952,
            "available_in_bytes" : 963459649536
          }
        ],
        "io_stats" : {
          "devices" : [
            {
              "device_name" : "nvme1n1",
              "operations" : 3336357,
              "read_operations" : 1313150,
              "write_operations" : 2023207,
              "read_kilobytes" : 9489196,
              "write_kilobytes" : 76926612
            }
          ],
          "total" : {
            "operations" : 3336357,
            "read_operations" : 1313150,
            "write_operations" : 2023207,
            "read_kilobytes" : 9489196,
            "write_kilobytes" : 76926612
          }
        }
      },
      "transport" : {
        "server_open" : 72,
        "rx_count" : 7860751,
        "rx_size_in_bytes" : 23275117293,
        "tx_count" : 7860750,
        "tx_size_in_bytes" : 28868535246
      },
      "http" : {
        "current_open" : 0,
        "total_opened" : 0
      },
      "breakers" : {
        "request" : {
          "limit_size_in_bytes" : 19259326464,
          "limit_size" : "17.9gb",
          "estimated_size_in_bytes" : 0,
          "estimated_size" : "0b",
          "overhead" : 1.0,
          "tripped" : 0
        },
        "fielddata" : {
          "limit_size_in_bytes" : 19259326464,
          "limit_size" : "17.9gb",
          "estimated_size_in_bytes" : 40489640,
          "estimated_size" : "38.6mb",
          "overhead" : 1.03,
          "tripped" : 0
        },
        "in_flight_requests" : {
          "limit_size_in_bytes" : 32098877440,
          "limit_size" : "29.8gb",
          "estimated_size_in_bytes" : 2041,
          "estimated_size" : "1.9kb",
          "overhead" : 1.0,
          "tripped" : 0
        },
        "accounting" : {
          "limit_size_in_bytes" : 32098877440,
          "limit_size" : "29.8gb",
          "estimated_size_in_bytes" : 76509700,
          "estimated_size" : "72.9mb",
          "overhead" : 1.0,
          "tripped" : 0
        },
        "parent" : {
          "limit_size_in_bytes" : 22469214208,
          "limit_size" : "20.9gb",
          "estimated_size_in_bytes" : 117001381,
          "estimated_size" : "111.5mb",
          "overhead" : 1.0,
          "tripped" : 0
        }
      },
      "script" : {
        "compilations" : 6,
        "cache_evictions" : 0
      },
      "discovery" : {
        "cluster_state_queue" : {
          "total" : 0,
          "pending" : 0,
          "committed" : 0
        },
        "published_cluster_states" : {
          "full_states" : 1,
          "incompatible_diffs" : 0,
          "compatible_diffs" : 667
        }
      },
      "ingest" : {
        "total" : {
          "count" : 0,
          "time_in_millis" : 0,
          "current" : 0,
          "failed" : 0
        },
        "pipelines" : {
          "xpack_monitoring_6" : {
            "count" : 0,
            "time_in_millis" : 0,
            "current" : 0,
            "failed" : 0
          },
          "xpack_monitoring_2" : {
            "count" : 0,
            "time_in_millis" : 0,
            "current" : 0,
            "failed" : 0
          }
        }
      },
      "adaptive_selection" : { }
    },
    "W3yuOmVHTu64L082AhqASQ" : {
      "timestamp" : 1552076357461,
      "name" : "ip-10-200-179-137.kdc.capitalone.com",
      "transport_address" : "10.200.179.137:9300",
      "host" : "10.200.179.137",
      "ip" : "10.200.179.137:9300",
      "roles" : [ ],
      "attributes" : {
        "aws_availability_zone" : "us-east-1a",
        "ml.machine_memory" : "16170377216",
        "xpack.installed" : "true",
        "ml.max_open_jobs" : "20",
        "ml.enabled" : "true"
      },
      "indices" : {
        "docs" : {
          "count" : 0,
          "deleted" : 0
        },
        "store" : {
          "size_in_bytes" : 0
        },
        "indexing" : {
          "index_total" : 0,
          "index_time_in_millis" : 0,
          "index_current" : 0,
          "index_failed" : 0,
          "delete_total" : 0,
          "delete_time_in_millis" : 0,
          "delete_current" : 0,
          "noop_update_total" : 0,
          "is_throttled" : false,
          "throttle_time_in_millis" : 0
        },
        "get" : {
          "total" : 0,
          "time_in_millis" : 0,
          "exists_total" : 0,
          "exists_time_in_millis" : 0,
          "missing_total" : 0,
          "missing_time_in_millis" : 0,
          "current" : 0
        },
        "search" : {
          "open_contexts" : 0,
          "query_total" : 0,
          "query_time_in_millis" : 0,
          "query_current" : 0,
          "fetch_total" : 0,
          "fetch_time_in_millis" : 0,
          "fetch_current" : 0,
          "scroll_total" : 0,
          "scroll_time_in_millis" : 0,
          "scroll_current" : 0,
          "suggest_total" : 0,
          "suggest_time_in_millis" : 0,
          "suggest_current" : 0
        },
        "merges" : {
          "current" : 0,
          "current_docs" : 0,
          "current_size_in_bytes" : 0,
          "total" : 0,
          "total_time_in_millis" : 0,
          "total_docs" : 0,
          "total_size_in_bytes" : 0,
          "total_stopped_time_in_millis" : 0,
          "total_throttled_time_in_millis" : 0,
          "total_auto_throttle_in_bytes" : 0
        },
        "refresh" : {
          "total" : 0,
          "total_time_in_millis" : 0,
          "listeners" : 0
        },
        "flush" : {
          "total" : 0,
          "periodic" : 0,
          "total_time_in_millis" : 0
        },
        "warmer" : {
          "current" : 0,
          "total" : 0,
          "total_time_in_millis" : 0
        },
        "query_cache" : {
          "memory_size_in_bytes" : 0,
          "total_count" : 0,
          "hit_count" : 0,
          "miss_count" : 0,
          "cache_size" : 0,
          "cache_count" : 0,
          "evictions" : 0
        },
        "fielddata" : {
          "memory_size_in_bytes" : 0,
          "evictions" : 0
        },
        "completion" : {
          "size_in_bytes" : 0
        },
        "segments" : {
          "count" : 0,
          "memory_in_bytes" : 0,
          "terms_memory_in_bytes" : 0,
          "stored_fields_memory_in_bytes" : 0,
          "term_vectors_memory_in_bytes" : 0,
          "norms_memory_in_bytes" : 0,
          "points_memory_in_bytes" : 0,
          "doc_values_memory_in_bytes" : 0,
          "index_writer_memory_in_bytes" : 0,
          "version_map_memory_in_bytes" : 0,
          "fixed_bit_set_memory_in_bytes" : 0,
          "max_unsafe_auto_id_timestamp" : -9223372036854775808,
          "file_sizes" : { }
        },
        "translog" : {
          "operations" : 0,
          "size_in_bytes" : 0,
          "uncommitted_operations" : 0,
          "uncommitted_size_in_bytes" : 0,
          "earliest_last_modified_age" : 0
        },
        "request_cache" : {
          "memory_size_in_bytes" : 0,
          "evictions" : 0,
          "hit_count" : 0,
          "miss_count" : 0
        },
        "recovery" : {
          "current_as_source" : 0,
          "current_as_target" : 0,
          "throttle_time_in_millis" : 0
        }
      },
      "os" : {
        "timestamp" : 1552076357463,
        "cpu" : {
          "percent" : 3,
          "load_average" : {
            "1m" : 0.11,
            "5m" : 0.15,
            "15m" : 0.14
          }
        },
        "mem" : {
          "total_in_bytes" : 16170377216,
          "free_in_bytes" : 4360749056,
          "used_in_bytes" : 11809628160,
          "free_percent" : 27,
          "used_percent" : 73
        },
        "swap" : {
          "total_in_bytes" : 0,
          "free_in_bytes" : 0,
          "used_in_bytes" : 0
        },
        "cgroup" : {
          "cpuacct" : {
            "control_group" : "/",
            "usage_nanos" : 21971575406450
          },
          "cpu" : {
            "control_group" : "/",
            "cfs_period_micros" : 100000,
            "cfs_quota_micros" : -1,
            "stat" : {
              "number_of_elapsed_periods" : 0,
              "number_of_times_throttled" : 0,
              "time_throttled_nanos" : 0
            }
          },
          "memory" : {
            "control_group" : "/system.slice/elasticsearch.service",
            "limit_in_bytes" : "9223372036854771712",
            "usage_in_bytes" : "457949184"
          }
        }
      },
      "process" : {
        "timestamp" : 1552076357463,
        "open_file_descriptors" : 507,
        "max_file_descriptors" : 65536,
        "cpu" : {
          "percent" : 1,
          "total_in_millis" : 3542270
        },
        "mem" : {
          "total_virtual_in_bytes" : 11726090240
        }
      },
      "jvm" : {
        "timestamp" : 1552076357463,
        "uptime_in_millis" : 179908250,
        "mem" : {
          "heap_used_in_bytes" : 5183750008,
          "heap_used_percent" : 69,
          "heap_committed_in_bytes" : 7481327616,
          "heap_max_in_bytes" : 7481327616,
          "non_heap_used_in_bytes" : 147709216,
          "non_heap_committed_in_bytes" : 158326784,
          "pools" : {
            "young" : {
              "used_in_bytes" : 204588296,
              "max_in_bytes" : 279183360,
              "peak_used_in_bytes" : 279183360,
              "peak_max_in_bytes" : 279183360
            },
            "survivor" : {
              "used_in_bytes" : 504592,
              "max_in_bytes" : 34865152,
              "peak_used_in_bytes" : 34865152,
              "peak_max_in_bytes" : 34865152
            },
            "old" : {
              "used_in_bytes" : 4978657120,
              "max_in_bytes" : 7167279104,
              "peak_used_in_bytes" : 5440541640,
              "peak_max_in_bytes" : 7167279104
            }
          }
        },
        "threads" : {
          "count" : 56,
          "peak_count" : 60
        },
        "gc" : {
          "collectors" : {
            "young" : {
              "collection_count" : 2325,
              "collection_time_in_millis" : 43691
            },
            "old" : {
              "collection_count" : 3,
              "collection_time_in_millis" : 174
            }
          }
        },
        "buffer_pools" : {
          "direct" : {
            "count" : 46,
            "used_in_bytes" : 270024713,
            "total_capacity_in_bytes" : 270024711
          },
          "mapped" : {
            "count" : 0,
            "used_in_bytes" : 0,
            "total_capacity_in_bytes" : 0
          }
        },
        "classes" : {
          "current_loaded_count" : 17602,
          "total_loaded_count" : 17747,
          "total_unloaded_count" : 145
        }
      },
      "thread_pool" : {
        "analyze" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "fetch_shard_started" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "fetch_shard_store" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "flush" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "force_merge" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "generic" : {
          "threads" : 4,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 4,
          "completed" : 558142
        },
        "get" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "index" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "listener" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "management" : {
          "threads" : 4,
          "queue" : 0,
          "active" : 1,
          "rejected" : 0,
          "largest" : 4,
          "completed" : 410343
        },
        "ml_autodetect" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "ml_datafeed" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "ml_utility" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "refresh" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "rollup_indexing" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "search" : {
          "threads" : 7,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 7,
          "completed" : 2177970
        },
        "snapshot" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "warmer" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "watcher" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "write" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        }
      },
      "fs" : {
        "timestamp" : 1552076357465,
        "total" : {
          "total_in_bytes" : 52710309888,
          "free_in_bytes" : 52629237760,
          "available_in_bytes" : 49928105984
        },
        "data" : [
          {
            "path" : "/opt/mount/var/data/myapp/elasticsearch/nodes/0",
            "mount" : "/opt/mount (/dev/nvme1n1)",
            "type" : "ext4",
            "total_in_bytes" : 52710309888,
            "free_in_bytes" : 52629237760,
            "available_in_bytes" : 49928105984
          }
        ],
        "io_stats" : {
          "devices" : [
            {
              "device_name" : "nvme1n1",
              "operations" : 57664,
              "read_operations" : 3,
              "write_operations" : 57661,
              "read_kilobytes" : 56,
              "write_kilobytes" : 361844
            }
          ],
          "total" : {
            "operations" : 57664,
            "read_operations" : 3,
            "write_operations" : 57661,
            "read_kilobytes" : 56,
            "write_kilobytes" : 361844
          }
        }
      },
      "transport" : {
        "server_open" : 75,
        "rx_count" : 18775613,
        "rx_size_in_bytes" : 27936398595,
        "tx_count" : 18775619,
        "tx_size_in_bytes" : 10860711246
      },
      "http" : {
        "current_open" : 69,
        "total_opened" : 325347
      },
      "breakers" : {
        "request" : {
          "limit_size_in_bytes" : 4488796569,
          "limit_size" : "4.1gb",
          "estimated_size_in_bytes" : 0,
          "estimated_size" : "0b",
          "overhead" : 1.0,
          "tripped" : 0
        },
        "fielddata" : {
          "limit_size_in_bytes" : 4488796569,
          "limit_size" : "4.1gb",
          "estimated_size_in_bytes" : 0,
          "estimated_size" : "0b",
          "overhead" : 1.03,
          "tripped" : 0
        },
        "in_flight_requests" : {
          "limit_size_in_bytes" : 7481327616,
          "limit_size" : "6.9gb",
          "estimated_size_in_bytes" : 0,
          "estimated_size" : "0b",
          "overhead" : 1.0,
          "tripped" : 0
        },
        "accounting" : {
          "limit_size_in_bytes" : 7481327616,
          "limit_size" : "6.9gb",
          "estimated_size_in_bytes" : 0,
          "estimated_size" : "0b",
          "overhead" : 1.0,
          "tripped" : 0
        },
        "parent" : {
          "limit_size_in_bytes" : 5236929331,
          "limit_size" : "4.8gb",
          "estimated_size_in_bytes" : 0,
          "estimated_size" : "0b",
          "overhead" : 1.0,
          "tripped" : 0
        }
      },
      "script" : {
        "compilations" : 6,
        "cache_evictions" : 0
      },
      "discovery" : {
        "cluster_state_queue" : {
          "total" : 0,
          "pending" : 0,
          "committed" : 0
        },
        "published_cluster_states" : {
          "full_states" : 1,
          "incompatible_diffs" : 0,
          "compatible_diffs" : 651
        }
      },
      "ingest" : {
        "total" : {
          "count" : 0,
          "time_in_millis" : 0,
          "current" : 0,
          "failed" : 0
        },
        "pipelines" : {
          "xpack_monitoring_2" : {
            "count" : 0,
            "time_in_millis" : 0,
            "current" : 0,
            "failed" : 0
          },
          "xpack_monitoring_6" : {
            "count" : 0,
            "time_in_millis" : 0,
            "current" : 0,
            "failed" : 0
          }
        }
      },
      "adaptive_selection" : {
        "OWya11Y4T4y2BfRMURk0wA" : {
          "outgoing_searches" : 0,
          "avg_queue_size" : 0,
          "avg_service_time_ns" : 229422,
          "avg_response_time_ns" : 656585,
          "rank" : "0.7"
        },
        "DZDySdQ-TNqWcxXBd1XAGQ" : {
          "outgoing_searches" : 0,
          "avg_queue_size" : 0,
          "avg_service_time_ns" : 175743,
          "avg_response_time_ns" : 787911,
          "rank" : "0.8"
        },
        "f492qWFDQyG8fkxNwf9mfQ" : {
          "outgoing_searches" : 0,
          "avg_queue_size" : 0,
          "avg_service_time_ns" : 163270,
          "avg_response_time_ns" : 1074669,
          "rank" : "1.1"
        },
        "zhMmgMtsRCGK5AgAR1_Vmw" : {
          "outgoing_searches" : 0,
          "avg_queue_size" : 0,
          "avg_service_time_ns" : 154236,
          "avg_response_time_ns" : 772038,
          "rank" : "0.8"
        },
        "TLp5t8ZGTWqSP4WTmzGcVg" : {
          "outgoing_searches" : 0,
          "avg_queue_size" : 0,
          "avg_service_time_ns" : 937774,
          "avg_response_time_ns" : 625253,
          "rank" : "0.6"
        }
      }
    },
    "TLp5t8ZGTWqSP4WTmzGcVg" : {
      "timestamp" : 1552076357462,
      "name" : "ip-10-200-177-6.kdc.capitalone.com",
      "transport_address" : "10.200.177.6:9300",
      "host" : "10.200.177.6",
      "ip" : "10.200.177.6:9300",
      "roles" : [
        "master",
        "data",
        "ingest"
      ],
      "attributes" : {
        "aws_availability_zone" : "us-east-1a",
        "ml.machine_memory" : "65842671616",
        "ml.max_open_jobs" : "20",
        "xpack.installed" : "true",
        "box_type" : "cold",
        "ml.enabled" : "true"
      },
      "indices" : {
        "docs" : {
          "count" : 4980479,
          "deleted" : 353139
        },
        "store" : {
          "size_in_bytes" : 38642681681
        },
        "indexing" : {
          "index_total" : 155017,
          "index_time_in_millis" : 306341,
          "index_current" : 0,
          "index_failed" : 2,
          "delete_total" : 0,
          "delete_time_in_millis" : 0,
          "delete_current" : 0,
          "noop_update_total" : 705,
          "is_throttled" : false,
          "throttle_time_in_millis" : 0
        },
        "get" : {
          "total" : 75143,
          "time_in_millis" : 13307,
          "exists_total" : 34449,
          "exists_time_in_millis" : 6729,
          "missing_total" : 40694,
          "missing_time_in_millis" : 6578,
          "current" : 0
        },
        "search" : {
          "open_contexts" : 1,
          "query_total" : 3536602,
          "query_time_in_millis" : 587549,
          "query_current" : 0,
          "fetch_total" : 127735,
          "fetch_time_in_millis" : 579062,
          "fetch_current" : 0,
          "scroll_total" : 337,
          "scroll_time_in_millis" : 44262969,
          "scroll_current" : 1,
          "suggest_total" : 0,
          "suggest_time_in_millis" : 0,
          "suggest_current" : 0
        },
        "merges" : {
          "current" : 0,
          "current_docs" : 0,
          "current_size_in_bytes" : 0,
          "total" : 11148,
          "total_time_in_millis" : 1240413,
          "total_docs" : 19150380,
          "total_size_in_bytes" : 25267878815,
          "total_stopped_time_in_millis" : 0,
          "total_throttled_time_in_millis" : 23195,
          "total_auto_throttle_in_bytes" : 1331746666
        },
        "refresh" : {
          "total" : 110929,
          "total_time_in_millis" : 2414404,
          "listeners" : 0
        },
        "flush" : {
          "total" : 538,
          "periodic" : 0,
          "total_time_in_millis" : 11078
        },
        "warmer" : {
          "current" : 0,
          "total" : 109762,
          "total_time_in_millis" : 5812
        },
        "query_cache" : {
          "memory_size_in_bytes" : 35188705,
          "total_count" : 4563064,
          "hit_count" : 281518,
          "miss_count" : 4281546,
          "cache_size" : 17218,
          "cache_count" : 17224,
          "evictions" : 6
        },
        "fielddata" : {
          "memory_size_in_bytes" : 42627472,
          "evictions" : 0
        },
        "completion" : {
          "size_in_bytes" : 0
        },
        "segments" : {
          "count" : 617,
          "memory_in_bytes" : 75546763,
          "terms_memory_in_bytes" : 62788636,
          "stored_fields_memory_in_bytes" : 7386712,
          "term_vectors_memory_in_bytes" : 0,
          "norms_memory_in_bytes" : 2668224,
          "points_memory_in_bytes" : 581499,
          "doc_values_memory_in_bytes" : 2121692,
          "index_writer_memory_in_bytes" : 0,
          "version_map_memory_in_bytes" : 0,
          "fixed_bit_set_memory_in_bytes" : 0,
          "max_unsafe_auto_id_timestamp" : 1546894432245,
          "file_sizes" : { }
        },
        "translog" : {
          "operations" : 43336,
          "size_in_bytes" : 289980563,
          "uncommitted_operations" : 41583,
          "uncommitted_size_in_bytes" : 280698532,
          "earliest_last_modified_age" : 0
        },
        "request_cache" : {
          "memory_size_in_bytes" : 41456633,
          "evictions" : 0,
          "hit_count" : 90794,
          "miss_count" : 67901
        },
        "recovery" : {
          "current_as_source" : 0,
          "current_as_target" : 0,
          "throttle_time_in_millis" : 1759546
        }
      },
      "os" : {
        "timestamp" : 1552076357546,
        "cpu" : {
          "percent" : 1,
          "load_average" : {
            "1m" : 0.09,
            "5m" : 0.08,
            "15m" : 0.1
          }
        },
        "mem" : {
          "total_in_bytes" : 65842671616,
          "free_in_bytes" : 481054720,
          "used_in_bytes" : 65361616896,
          "free_percent" : 1,
          "used_percent" : 99
        },
        "swap" : {
          "total_in_bytes" : 0,
          "free_in_bytes" : 0,
          "used_in_bytes" : 0
        },
        "cgroup" : {
          "cpuacct" : {
            "control_group" : "/",
            "usage_nanos" : 33400568268976
          },
          "cpu" : {
            "control_group" : "/",
            "cfs_period_micros" : 100000,
            "cfs_quota_micros" : -1,
            "stat" : {
              "number_of_elapsed_periods" : 0,
              "number_of_times_throttled" : 0,
              "time_throttled_nanos" : 0
            }
          },
          "memory" : {
            "control_group" : "/system.slice/elasticsearch.service",
            "limit_in_bytes" : "9223372036854771712",
            "usage_in_bytes" : "28704772096"
          }
        }
      },
      "process" : {
        "timestamp" : 1552076357546,
        "open_file_descriptors" : 908,
        "max_file_descriptors" : 65536,
        "cpu" : {
          "percent" : 1,
          "total_in_millis" : 14923680
        },
        "mem" : {
          "total_virtual_in_bytes" : 82320400384
        }
      },
      "jvm" : {
        "timestamp" : 1552076357547,
        "uptime_in_millis" : 180109435,
        "mem" : {
          "heap_used_in_bytes" : 7200896320,
          "heap_used_percent" : 22,
          "heap_committed_in_bytes" : 32098877440,
          "heap_max_in_bytes" : 32098877440,
          "non_heap_used_in_bytes" : 195032416,
          "non_heap_committed_in_bytes" : 205811712,
          "pools" : {
            "young" : {
              "used_in_bytes" : 554854056,
              "max_in_bytes" : 907345920,
              "peak_used_in_bytes" : 907345920,
              "peak_max_in_bytes" : 907345920
            },
            "survivor" : {
              "used_in_bytes" : 10048272,
              "max_in_bytes" : 113377280,
              "peak_used_in_bytes" : 113377280,
              "peak_max_in_bytes" : 113377280
            },
            "old" : {
              "used_in_bytes" : 6635993992,
              "max_in_bytes" : 31078154240,
              "peak_used_in_bytes" : 6635993992,
              "peak_max_in_bytes" : 31078154240
            }
          }
        },
        "threads" : {
          "count" : 178,
          "peak_count" : 183
        },
        "gc" : {
          "collectors" : {
            "young" : {
              "collection_count" : 18734,
              "collection_time_in_millis" : 643178
            },
            "old" : {
              "collection_count" : 2,
              "collection_time_in_millis" : 93
            }
          }
        },
        "buffer_pools" : {
          "direct" : {
            "count" : 219,
            "used_in_bytes" : 541424466,
            "total_capacity_in_bytes" : 541424465
          },
          "mapped" : {
            "count" : 1245,
            "used_in_bytes" : 38527104064,
            "total_capacity_in_bytes" : 38527104064
          }
        },
        "classes" : {
          "current_loaded_count" : 19400,
          "total_loaded_count" : 19400,
          "total_unloaded_count" : 0
        }
      },
      "thread_pool" : {
        "analyze" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "fetch_shard_started" : {
          "threads" : 1,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 9,
          "completed" : 131
        },
        "fetch_shard_store" : {
          "threads" : 1,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 16,
          "completed" : 131
        },
        "flush" : {
          "threads" : 1,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 4,
          "completed" : 1063
        },
        "force_merge" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "generic" : {
          "threads" : 8,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 8,
          "completed" : 776989
        },
        "get" : {
          "threads" : 16,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 16,
          "completed" : 26
        },
        "index" : {
          "threads" : 16,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 16,
          "completed" : 870
        },
        "listener" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "management" : {
          "threads" : 3,
          "queue" : 0,
          "active" : 1,
          "rejected" : 0,
          "largest" : 3,
          "completed" : 447414
        },
        "ml_autodetect" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "ml_datafeed" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "ml_utility" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "refresh" : {
          "threads" : 8,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 8,
          "completed" : 5006863
        },
        "rollup_indexing" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "search" : {
          "threads" : 25,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 25,
          "completed" : 3664395
        },
        "security-token-key" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "snapshot" : {
          "threads" : 1,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 5,
          "completed" : 60
        },
        "warmer" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "watcher" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "write" : {
          "threads" : 16,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 16,
          "completed" : 152524
        }
      },
      "fs" : {
        "timestamp" : 1552076357548,
        "total" : {
          "total_in_bytes" : 1056755048448,
          "free_in_bytes" : 1017729171456,
          "available_in_bytes" : 964025303040
        },
        "data" : [
          {
            "path" : "/opt/mount/var/data/myapp/elasticsearch/nodes/0",
            "mount" : "/opt/mount (/dev/nvme1n1)",
            "type" : "ext4",
            "total_in_bytes" : 1056755048448,
            "free_in_bytes" : 1017729171456,
            "available_in_bytes" : 964025303040
          }
        ],
        "io_stats" : {
          "devices" : [
            {
              "device_name" : "nvme1n1",
              "operations" : 3338887,
              "read_operations" : 1243237,
              "write_operations" : 2095650,
              "read_kilobytes" : 9471496,
              "write_kilobytes" : 81398708
            }
          ],
          "total" : {
            "operations" : 3338887,
            "read_operations" : 1243237,
            "write_operations" : 2095650,
            "read_kilobytes" : 9471496,
            "write_kilobytes" : 81398708
          }
        }
      },
      "transport" : {
        "server_open" : 72,
        "rx_count" : 7873754,
        "rx_size_in_bytes" : 25974844222,
        "tx_count" : 7873753,
        "tx_size_in_bytes" : 34262756268
      },
      "http" : {
        "current_open" : 0,
        "total_opened" : 0
      },
      "breakers" : {
        "request" : {
          "limit_size_in_bytes" : 19259326464,
          "limit_size" : "17.9gb",
          "estimated_size_in_bytes" : 0,
          "estimated_size" : "0b",
          "overhead" : 1.0,
          "tripped" : 0
        },
        "fielddata" : {
          "limit_size_in_bytes" : 19259326464,
          "limit_size" : "17.9gb",
          "estimated_size_in_bytes" : 42627472,
          "estimated_size" : "40.6mb",
          "overhead" : 1.03,
          "tripped" : 0
        },
        "in_flight_requests" : {
          "limit_size_in_bytes" : 32098877440,
          "limit_size" : "29.8gb",
          "estimated_size_in_bytes" : 2041,
          "estimated_size" : "1.9kb",
          "overhead" : 1.0,
          "tripped" : 0
        },
        "accounting" : {
          "limit_size_in_bytes" : 32098877440,
          "limit_size" : "29.8gb",
          "estimated_size_in_bytes" : 75546763,
          "estimated_size" : "72mb",
          "overhead" : 1.0,
          "tripped" : 0
        },
        "parent" : {
          "limit_size_in_bytes" : 22469214208,
          "limit_size" : "20.9gb",
          "estimated_size_in_bytes" : 118176276,
          "estimated_size" : "112.7mb",
          "overhead" : 1.0,
          "tripped" : 0
        }
      },
      "script" : {
        "compilations" : 6,
        "cache_evictions" : 0
      },
      "discovery" : {
        "cluster_state_queue" : {
          "total" : 0,
          "pending" : 0,
          "committed" : 0
        },
        "published_cluster_states" : {
          "full_states" : 1,
          "incompatible_diffs" : 0,
          "compatible_diffs" : 652
        }
      },
      "ingest" : {
        "total" : {
          "count" : 0,
          "time_in_millis" : 0,
          "current" : 0,
          "failed" : 0
        },
        "pipelines" : {
          "xpack_monitoring_2" : {
            "count" : 0,
            "time_in_millis" : 0,
            "current" : 0,
            "failed" : 0
          },
          "xpack_monitoring_6" : {
            "count" : 0,
            "time_in_millis" : 0,
            "current" : 0,
            "failed" : 0
          }
        }
      },
      "adaptive_selection" : { }
    },
    "DZDySdQ-TNqWcxXBd1XAGQ" : {
      "timestamp" : 1552076357462,
      "name" : "ip-10-200-186-11.kdc.capitalone.com",
      "transport_address" : "10.200.186.11:9300",
      "host" : "10.200.186.11",
      "ip" : "10.200.186.11:9300",
      "roles" : [
        "master",
        "data",
        "ingest"
      ],
      "attributes" : {
        "aws_availability_zone" : "us-east-1b",
        "ml.machine_memory" : "65842671616",
        "ml.max_open_jobs" : "20",
        "xpack.installed" : "true",
        "box_type" : "cold",
        "ml.enabled" : "true"
      },
      "indices" : {
        "docs" : {
          "count" : 4982065,
          "deleted" : 345030
        },
        "store" : {
          "size_in_bytes" : 38655660744
        },
        "indexing" : {
          "index_total" : 153606,
          "index_time_in_millis" : 308318,
          "index_current" : 0,
          "index_failed" : 4,
          "delete_total" : 1,
          "delete_time_in_millis" : 5,
          "delete_current" : 0,
          "noop_update_total" : 742,
          "is_throttled" : false,
          "throttle_time_in_millis" : 0
        },
        "get" : {
          "total" : 157368,
          "time_in_millis" : 17263,
          "exists_total" : 116733,
          "exists_time_in_millis" : 10475,
          "missing_total" : 40635,
          "missing_time_in_millis" : 6788,
          "current" : 0
        },
        "search" : {
          "open_contexts" : 1,
          "query_total" : 3612172,
          "query_time_in_millis" : 621470,
          "query_current" : 0,
          "fetch_total" : 200927,
          "fetch_time_in_millis" : 606087,
          "fetch_current" : 0,
          "scroll_total" : 335,
          "scroll_time_in_millis" : 44280415,
          "scroll_current" : 1,
          "suggest_total" : 0,
          "suggest_time_in_millis" : 0,
          "suggest_current" : 0
        },
        "merges" : {
          "current" : 0,
          "current_docs" : 0,
          "current_size_in_bytes" : 0,
          "total" : 11133,
          "total_time_in_millis" : 1229785,
          "total_docs" : 19272184,
          "total_size_in_bytes" : 24831312344,
          "total_stopped_time_in_millis" : 0,
          "total_throttled_time_in_millis" : 11039,
          "total_auto_throttle_in_bytes" : 1334897908
        },
        "refresh" : {
          "total" : 110926,
          "total_time_in_millis" : 2427609,
          "listeners" : 0
        },
        "flush" : {
          "total" : 541,
          "periodic" : 0,
          "total_time_in_millis" : 8414
        },
        "warmer" : {
          "current" : 0,
          "total" : 109759,
          "total_time_in_millis" : 6176
        },
        "query_cache" : {
          "memory_size_in_bytes" : 35688551,
          "total_count" : 4660990,
          "hit_count" : 282565,
          "miss_count" : 4378425,
          "cache_size" : 16897,
          "cache_count" : 16901,
          "evictions" : 4
        },
        "fielddata" : {
          "memory_size_in_bytes" : 41764892,
          "evictions" : 0
        },
        "completion" : {
          "size_in_bytes" : 0
        },
        "segments" : {
          "count" : 637,
          "memory_in_bytes" : 76158868,
          "terms_memory_in_bytes" : 63483087,
          "stored_fields_memory_in_bytes" : 7386904,
          "term_vectors_memory_in_bytes" : 0,
          "norms_memory_in_bytes" : 2672576,
          "points_memory_in_bytes" : 584681,
          "doc_values_memory_in_bytes" : 2031620,
          "index_writer_memory_in_bytes" : 3490200,
          "version_map_memory_in_bytes" : 316,
          "fixed_bit_set_memory_in_bytes" : 0,
          "max_unsafe_auto_id_timestamp" : 1550088567387,
          "file_sizes" : { }
        },
        "translog" : {
          "operations" : 42648,
          "size_in_bytes" : 283935273,
          "uncommitted_operations" : 40804,
          "uncommitted_size_in_bytes" : 273770126,
          "earliest_last_modified_age" : 0
        },
        "request_cache" : {
          "memory_size_in_bytes" : 41460466,
          "evictions" : 0,
          "hit_count" : 162260,
          "miss_count" : 67912
        },
        "recovery" : {
          "current_as_source" : 0,
          "current_as_target" : 0,
          "throttle_time_in_millis" : 1281880
        }
      },
      "os" : {
        "timestamp" : 1552076357552,
        "cpu" : {
          "percent" : 1,
          "load_average" : {
            "1m" : 0.2,
            "5m" : 0.19,
            "15m" : 0.22
          }
        },
        "mem" : {
          "total_in_bytes" : 65842671616,
          "free_in_bytes" : 456798208,
          "used_in_bytes" : 65385873408,
          "free_percent" : 1,
          "used_percent" : 99
        },
        "swap" : {
          "total_in_bytes" : 0,
          "free_in_bytes" : 0,
          "used_in_bytes" : 0
        },
        "cgroup" : {
          "cpuacct" : {
            "control_group" : "/",
            "usage_nanos" : 33823832879687
          },
          "cpu" : {
            "control_group" : "/",
            "cfs_period_micros" : 100000,
            "cfs_quota_micros" : -1,
            "stat" : {
              "number_of_elapsed_periods" : 0,
              "number_of_times_throttled" : 0,
              "time_throttled_nanos" : 0
            }
          },
          "memory" : {
            "control_group" : "/system.slice/elasticsearch.service",
            "limit_in_bytes" : "9223372036854771712",
            "usage_in_bytes" : "28401233920"
          }
        }
      },
      "process" : {
        "timestamp" : 1552076357553,
        "open_file_descriptors" : 915,
        "max_file_descriptors" : 65536,
        "cpu" : {
          "percent" : 1,
          "total_in_millis" : 15355690
        },
        "mem" : {
          "total_virtual_in_bytes" : 82350157824
        }
      },
      "jvm" : {
        "timestamp" : 1552076357553,
        "uptime_in_millis" : 180111682,
        "mem" : {
          "heap_used_in_bytes" : 6568242280,
          "heap_used_percent" : 20,
          "heap_committed_in_bytes" : 32098877440,
          "heap_max_in_bytes" : 32098877440,
          "non_heap_used_in_bytes" : 198397856,
          "non_heap_committed_in_bytes" : 209391616,
          "pools" : {
            "young" : {
              "used_in_bytes" : 839399488,
              "max_in_bytes" : 907345920,
              "peak_used_in_bytes" : 907345920,
              "peak_max_in_bytes" : 907345920
            },
            "survivor" : {
              "used_in_bytes" : 16602432,
              "max_in_bytes" : 113377280,
              "peak_used_in_bytes" : 113377280,
              "peak_max_in_bytes" : 113377280
            },
            "old" : {
              "used_in_bytes" : 5712240360,
              "max_in_bytes" : 31078154240,
              "peak_used_in_bytes" : 5712240360,
              "peak_max_in_bytes" : 31078154240
            }
          }
        },
        "threads" : {
          "count" : 187,
          "peak_count" : 192
        },
        "gc" : {
          "collectors" : {
            "young" : {
              "collection_count" : 18707,
              "collection_time_in_millis" : 660009
            },
            "old" : {
              "collection_count" : 2,
              "collection_time_in_millis" : 106
            }
          }
        },
        "buffer_pools" : {
          "direct" : {
            "count" : 162,
            "used_in_bytes" : 541545668,
            "total_capacity_in_bytes" : 541545667
          },
          "mapped" : {
            "count" : 1253,
            "used_in_bytes" : 38547205564,
            "total_capacity_in_bytes" : 38547205564
          }
        },
        "classes" : {
          "current_loaded_count" : 19355,
          "total_loaded_count" : 19355,
          "total_unloaded_count" : 0
        }
      },
      "thread_pool" : {
        "analyze" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "fetch_shard_started" : {
          "threads" : 1,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 21,
          "completed" : 131
        },
        "fetch_shard_store" : {
          "threads" : 1,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 25,
          "completed" : 131
        },
        "flush" : {
          "threads" : 1,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 4,
          "completed" : 1069
        },
        "force_merge" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "generic" : {
          "threads" : 8,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 8,
          "completed" : 777668
        },
        "get" : {
          "threads" : 16,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 16,
          "completed" : 80563
        },
        "index" : {
          "threads" : 16,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 16,
          "completed" : 867
        },
        "listener" : {
          "threads" : 8,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 8,
          "completed" : 37
        },
        "management" : {
          "threads" : 4,
          "queue" : 0,
          "active" : 1,
          "rejected" : 0,
          "largest" : 4,
          "completed" : 446434
        },
        "ml_autodetect" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "ml_datafeed" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "ml_utility" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "refresh" : {
          "threads" : 8,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 8,
          "completed" : 5185404
        },
        "rollup_indexing" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "search" : {
          "threads" : 25,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 25,
          "completed" : 3736720
        },
        "security-token-key" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "snapshot" : {
          "threads" : 1,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 5,
          "completed" : 56
        },
        "warmer" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "watcher" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "write" : {
          "threads" : 16,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 16,
          "completed" : 151423
        }
      },
      "fs" : {
        "timestamp" : 1552076357554,
        "total" : {
          "total_in_bytes" : 1056755048448,
          "free_in_bytes" : 1017722888192,
          "available_in_bytes" : 964019019776
        },
        "data" : [
          {
            "path" : "/opt/mount/var/data/myapp/elasticsearch/nodes/0",
            "mount" : "/opt/mount (/dev/nvme1n1)",
            "type" : "ext4",
            "total_in_bytes" : 1056755048448,
            "free_in_bytes" : 1017722888192,
            "available_in_bytes" : 964019019776
          }
        ],
        "io_stats" : {
          "devices" : [
            {
              "device_name" : "nvme1n1",
              "operations" : 3242130,
              "read_operations" : 1179670,
              "write_operations" : 2062460,
              "read_kilobytes" : 8400644,
              "write_kilobytes" : 76271140
            }
          ],
          "total" : {
            "operations" : 3242130,
            "read_operations" : 1179670,
            "write_operations" : 2062460,
            "read_kilobytes" : 8400644,
            "write_kilobytes" : 76271140
          }
        }
      },
      "transport" : {
        "server_open" : 72,
        "rx_count" : 8011324,
        "rx_size_in_bytes" : 23193693985,
        "tx_count" : 8011323,
        "tx_size_in_bytes" : 29412864635
      },
      "http" : {
        "current_open" : 0,
        "total_opened" : 0
      },
      "breakers" : {
        "request" : {
          "limit_size_in_bytes" : 19259326464,
          "limit_size" : "17.9gb",
          "estimated_size_in_bytes" : 0,
          "estimated_size" : "0b",
          "overhead" : 1.0,
          "tripped" : 0
        },
        "fielddata" : {
          "limit_size_in_bytes" : 19259326464,
          "limit_size" : "17.9gb",
          "estimated_size_in_bytes" : 41764892,
          "estimated_size" : "39.8mb",
          "overhead" : 1.03,
          "tripped" : 0
        },
        "in_flight_requests" : {
          "limit_size_in_bytes" : 32098877440,
          "limit_size" : "29.8gb",
          "estimated_size_in_bytes" : 2041,
          "estimated_size" : "1.9kb",
          "overhead" : 1.0,
          "tripped" : 0
        },
        "accounting" : {
          "limit_size_in_bytes" : 32098877440,
          "limit_size" : "29.8gb",
          "estimated_size_in_bytes" : 76158868,
          "estimated_size" : "72.6mb",
          "overhead" : 1.0,
          "tripped" : 0
        },
        "parent" : {
          "limit_size_in_bytes" : 22469214208,
          "limit_size" : "20.9gb",
          "estimated_size_in_bytes" : 117925801,
          "estimated_size" : "112.4mb",
          "overhead" : 1.0,
          "tripped" : 0
        }
      },
      "script" : {
        "compilations" : 6,
        "cache_evictions" : 0
      },
      "discovery" : {
        "cluster_state_queue" : {
          "total" : 0,
          "pending" : 0,
          "committed" : 0
        },
        "published_cluster_states" : {
          "full_states" : 1,
          "incompatible_diffs" : 0,
          "compatible_diffs" : 653
        }
      },
      "ingest" : {
        "total" : {
          "count" : 0,
          "time_in_millis" : 0,
          "current" : 0,
          "failed" : 0
        },
        "pipelines" : {
          "xpack_monitoring_2" : {
            "count" : 0,
            "time_in_millis" : 0,
            "current" : 0,
            "failed" : 0
          },
          "xpack_monitoring_6" : {
            "count" : 0,
            "time_in_millis" : 0,
            "current" : 0,
            "failed" : 0
          }
        }
      },
      "adaptive_selection" : { }
    },
    "zhMmgMtsRCGK5AgAR1_Vmw" : {
      "timestamp" : 1552076357462,
      "name" : "ip-10-200-186-208.kdc.capitalone.com",
      "transport_address" : "10.200.186.208:9300",
      "host" : "10.200.186.208",
      "ip" : "10.200.186.208:9300",
      "roles" : [
        "master",
        "data",
        "ingest"
      ],
      "attributes" : {
        "aws_availability_zone" : "us-east-1b",
        "ml.machine_memory" : "65842671616",
        "ml.max_open_jobs" : "20",
        "xpack.installed" : "true",
        "box_type" : "hot",
        "ml.enabled" : "true"
      },
      "indices" : {
        "docs" : {
          "count" : 4984325,
          "deleted" : 363614
        },
        "store" : {
          "size_in_bytes" : 39076419987
        },
        "indexing" : {
          "index_total" : 155032,
          "index_time_in_millis" : 308647,
          "index_current" : 0,
          "index_failed" : 0,
          "delete_total" : 0,
          "delete_time_in_millis" : 0,
          "delete_current" : 0,
          "noop_update_total" : 692,
          "is_throttled" : false,
          "throttle_time_in_millis" : 0
        },
        "get" : {
          "total" : 75676,
          "time_in_millis" : 13746,
          "exists_total" : 34692,
          "exists_time_in_millis" : 6766,
          "missing_total" : 40984,
          "missing_time_in_millis" : 6980,
          "current" : 0
        },
        "search" : {
          "open_contexts" : 2,
          "query_total" : 3540306,
          "query_time_in_millis" : 654260,
          "query_current" : 0,
          "fetch_total" : 123867,
          "fetch_time_in_millis" : 473174,
          "fetch_current" : 0,
          "scroll_total" : 344,
          "scroll_time_in_millis" : 45316362,
          "scroll_current" : 2,
          "suggest_total" : 0,
          "suggest_time_in_millis" : 0,
          "suggest_current" : 0
        },
        "merges" : {
          "current" : 0,
          "current_docs" : 0,
          "current_size_in_bytes" : 0,
          "total" : 11132,
          "total_time_in_millis" : 1257959,
          "total_docs" : 19184982,
          "total_size_in_bytes" : 25637467753,
          "total_stopped_time_in_millis" : 0,
          "total_throttled_time_in_millis" : 32494,
          "total_auto_throttle_in_bytes" : 1308040596
        },
        "refresh" : {
          "total" : 110676,
          "total_time_in_millis" : 2437473,
          "listeners" : 0
        },
        "flush" : {
          "total" : 519,
          "periodic" : 0,
          "total_time_in_millis" : 9665
        },
        "warmer" : {
          "current" : 0,
          "total" : 109539,
          "total_time_in_millis" : 5671
        },
        "query_cache" : {
          "memory_size_in_bytes" : 35796238,
          "total_count" : 3769748,
          "hit_count" : 222064,
          "miss_count" : 3547684,
          "cache_size" : 14175,
          "cache_count" : 14181,
          "evictions" : 6
        },
        "fielddata" : {
          "memory_size_in_bytes" : 41593256,
          "evictions" : 0
        },
        "completion" : {
          "size_in_bytes" : 0
        },
        "segments" : {
          "count" : 601,
          "memory_in_bytes" : 75043080,
          "terms_memory_in_bytes" : 61920956,
          "stored_fields_memory_in_bytes" : 7401952,
          "term_vectors_memory_in_bytes" : 0,
          "norms_memory_in_bytes" : 2602432,
          "points_memory_in_bytes" : 580640,
          "doc_values_memory_in_bytes" : 2537100,
          "index_writer_memory_in_bytes" : 0,
          "version_map_memory_in_bytes" : 0,
          "fixed_bit_set_memory_in_bytes" : 0,
          "max_unsafe_auto_id_timestamp" : 1550721329971,
          "file_sizes" : { }
        },
        "translog" : {
          "operations" : 43446,
          "size_in_bytes" : 289488756,
          "uncommitted_operations" : 41686,
          "uncommitted_size_in_bytes" : 279467378,
          "earliest_last_modified_age" : 0
        },
        "request_cache" : {
          "memory_size_in_bytes" : 41660176,
          "evictions" : 0,
          "hit_count" : 91471,
          "miss_count" : 66457
        },
        "recovery" : {
          "current_as_source" : 0,
          "current_as_target" : 0,
          "throttle_time_in_millis" : 1388486
        }
      },
      "os" : {
        "timestamp" : 1552076357546,
        "cpu" : {
          "percent" : 1,
          "load_average" : {
            "1m" : 0.14,
            "5m" : 0.16,
            "15m" : 0.16
          }
        },
        "mem" : {
          "total_in_bytes" : 65842671616,
          "free_in_bytes" : 520368128,
          "used_in_bytes" : 65322303488,
          "free_percent" : 1,
          "used_percent" : 99
        },
        "swap" : {
          "total_in_bytes" : 0,
          "free_in_bytes" : 0,
          "used_in_bytes" : 0
        },
        "cgroup" : {
          "cpuacct" : {
            "control_group" : "/",
            "usage_nanos" : 33391870583988
          },
          "cpu" : {
            "control_group" : "/",
            "cfs_period_micros" : 100000,
            "cfs_quota_micros" : -1,
            "stat" : {
              "number_of_elapsed_periods" : 0,
              "number_of_times_throttled" : 0,
              "time_throttled_nanos" : 0
            }
          },
          "memory" : {
            "control_group" : "/system.slice/elasticsearch.service",
            "limit_in_bytes" : "9223372036854771712",
            "usage_in_bytes" : "28470472704"
          }
        }
      },
      "process" : {
        "timestamp" : 1552076357546,
        "open_file_descriptors" : 894,
        "max_file_descriptors" : 65536,
        "cpu" : {
          "percent" : 1,
          "total_in_millis" : 14983100
        },
        "mem" : {
          "total_virtual_in_bytes" : 82523435008
        }
      },
      "jvm" : {
        "timestamp" : 1552076357546,
        "uptime_in_millis" : 180124148,
        "mem" : {
          "heap_used_in_bytes" : 7620645928,
          "heap_used_percent" : 23,
          "heap_committed_in_bytes" : 32098877440,
          "heap_max_in_bytes" : 32098877440,
          "non_heap_used_in_bytes" : 196677912,
          "non_heap_committed_in_bytes" : 208080896,
          "pools" : {
            "young" : {
              "used_in_bytes" : 724705744,
              "max_in_bytes" : 907345920,
              "peak_used_in_bytes" : 907345920,
              "peak_max_in_bytes" : 907345920
            },
            "survivor" : {
              "used_in_bytes" : 15316184,
              "max_in_bytes" : 113377280,
              "peak_used_in_bytes" : 113377280,
              "peak_max_in_bytes" : 113377280
            },
            "old" : {
              "used_in_bytes" : 6880666720,
              "max_in_bytes" : 31078154240,
              "peak_used_in_bytes" : 6880666720,
              "peak_max_in_bytes" : 31078154240
            }
          }
        },
        "threads" : {
          "count" : 179,
          "peak_count" : 184
        },
        "gc" : {
          "collectors" : {
            "young" : {
              "collection_count" : 18437,
              "collection_time_in_millis" : 642692
            },
            "old" : {
              "collection_count" : 2,
              "collection_time_in_millis" : 97
            }
          }
        },
        "buffer_pools" : {
          "direct" : {
            "count" : 228,
            "used_in_bytes" : 541688112,
            "total_capacity_in_bytes" : 541688111
          },
          "mapped" : {
            "count" : 1181,
            "used_in_bytes" : 38662146978,
            "total_capacity_in_bytes" : 38662146978
          }
        },
        "classes" : {
          "current_loaded_count" : 19356,
          "total_loaded_count" : 19356,
          "total_unloaded_count" : 0
        }
      },
      "thread_pool" : {
        "analyze" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "fetch_shard_started" : {
          "threads" : 1,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 18,
          "completed" : 131
        },
        "fetch_shard_store" : {
          "threads" : 1,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 15,
          "completed" : 131
        },
        "flush" : {
          "threads" : 1,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 3,
          "completed" : 1026
        },
        "force_merge" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "generic" : {
          "threads" : 8,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 8,
          "completed" : 771257
        },
        "get" : {
          "threads" : 16,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 16,
          "completed" : 24
        },
        "index" : {
          "threads" : 16,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 16,
          "completed" : 808
        },
        "listener" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "management" : {
          "threads" : 4,
          "queue" : 0,
          "active" : 1,
          "rejected" : 0,
          "largest" : 4,
          "completed" : 447541
        },
        "ml_autodetect" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "ml_datafeed" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "ml_utility" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "refresh" : {
          "threads" : 8,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 8,
          "completed" : 5006829
        },
        "rollup_indexing" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "search" : {
          "threads" : 25,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 25,
          "completed" : 3664235
        },
        "security-token-key" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "snapshot" : {
          "threads" : 1,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 5,
          "completed" : 60
        },
        "warmer" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "watcher" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "write" : {
          "threads" : 16,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 16,
          "completed" : 152666
        }
      },
      "fs" : {
        "timestamp" : 1552076357548,
        "total" : {
          "total_in_bytes" : 1056755048448,
          "free_in_bytes" : 1017296654336,
          "available_in_bytes" : 963592785920
        },
        "data" : [
          {
            "path" : "/opt/mount/var/data/myapp/elasticsearch/nodes/0",
            "mount" : "/opt/mount (/dev/nvme1n1)",
            "type" : "ext4",
            "total_in_bytes" : 1056755048448,
            "free_in_bytes" : 1017296654336,
            "available_in_bytes" : 963592785920
          }
        ],
        "io_stats" : {
          "devices" : [
            {
              "device_name" : "nvme1n1",
              "operations" : 3032651,
              "read_operations" : 1073609,
              "write_operations" : 1959042,
              "read_kilobytes" : 8350084,
              "write_kilobytes" : 75718220
            }
          ],
          "total" : {
            "operations" : 3032651,
            "read_operations" : 1073609,
            "write_operations" : 1959042,
            "read_kilobytes" : 8350084,
            "write_kilobytes" : 75718220
          }
        }
      },
      "transport" : {
        "server_open" : 72,
        "rx_count" : 7861790,
        "rx_size_in_bytes" : 23079242157,
        "tx_count" : 7861789,
        "tx_size_in_bytes" : 28303175563
      },
      "http" : {
        "current_open" : 0,
        "total_opened" : 0
      },
      "breakers" : {
        "request" : {
          "limit_size_in_bytes" : 19259326464,
          "limit_size" : "17.9gb",
          "estimated_size_in_bytes" : 0,
          "estimated_size" : "0b",
          "overhead" : 1.0,
          "tripped" : 0
        },
        "fielddata" : {
          "limit_size_in_bytes" : 19259326464,
          "limit_size" : "17.9gb",
          "estimated_size_in_bytes" : 41593256,
          "estimated_size" : "39.6mb",
          "overhead" : 1.03,
          "tripped" : 0
        },
        "in_flight_requests" : {
          "limit_size_in_bytes" : 32098877440,
          "limit_size" : "29.8gb",
          "estimated_size_in_bytes" : 2041,
          "estimated_size" : "1.9kb",
          "overhead" : 1.0,
          "tripped" : 0
        },
        "accounting" : {
          "limit_size_in_bytes" : 32098877440,
          "limit_size" : "29.8gb",
          "estimated_size_in_bytes" : 75043080,
          "estimated_size" : "71.5mb",
          "overhead" : 1.0,
          "tripped" : 0
        },
        "parent" : {
          "limit_size_in_bytes" : 22469214208,
          "limit_size" : "20.9gb",
          "estimated_size_in_bytes" : 116638377,
          "estimated_size" : "111.2mb",
          "overhead" : 1.0,
          "tripped" : 0
        }
      },
      "script" : {
        "compilations" : 6,
        "cache_evictions" : 0
      },
      "discovery" : {
        "cluster_state_queue" : {
          "total" : 0,
          "pending" : 0,
          "committed" : 0
        },
        "published_cluster_states" : {
          "full_states" : 1,
          "incompatible_diffs" : 0,
          "compatible_diffs" : 667
        }
      },
      "ingest" : {
        "total" : {
          "count" : 0,
          "time_in_millis" : 0,
          "current" : 0,
          "failed" : 0
        },
        "pipelines" : {
          "xpack_monitoring_6" : {
            "count" : 0,
            "time_in_millis" : 0,
            "current" : 0,
            "failed" : 0
          },
          "xpack_monitoring_2" : {
            "count" : 0,
            "time_in_millis" : 0,
            "current" : 0,
            "failed" : 0
          }
        }
      },
      "adaptive_selection" : { }
    },
    "OWya11Y4T4y2BfRMURk0wA" : {
      "timestamp" : 1552076357462,
      "name" : "ip-10-200-177-190.kdc.capitalone.com",
      "transport_address" : "10.200.177.190:9300",
      "host" : "10.200.177.190",
      "ip" : "10.200.177.190:9300",
      "roles" : [
        "master",
        "data",
        "ingest"
      ],
      "attributes" : {
        "aws_availability_zone" : "us-east-1a",
        "ml.machine_memory" : "65842671616",
        "ml.max_open_jobs" : "20",
        "xpack.installed" : "true",
        "box_type" : "hot",
        "ml.enabled" : "true"
      },
      "indices" : {
        "docs" : {
          "count" : 4983338,
          "deleted" : 425373
        },
        "store" : {
          "size_in_bytes" : 39491408043
        },
        "indexing" : {
          "index_total" : 153914,
          "index_time_in_millis" : 308984,
          "index_current" : 0,
          "index_failed" : 0,
          "delete_total" : 1,
          "delete_time_in_millis" : 7,
          "delete_current" : 0,
          "noop_update_total" : 756,
          "is_throttled" : false,
          "throttle_time_in_millis" : 0
        },
        "get" : {
          "total" : 156118,
          "time_in_millis" : 16449,
          "exists_total" : 115594,
          "exists_time_in_millis" : 10016,
          "missing_total" : 40524,
          "missing_time_in_millis" : 6433,
          "current" : 0
        },
        "search" : {
          "open_contexts" : 0,
          "query_total" : 3613311,
          "query_time_in_millis" : 758694,
          "query_current" : 0,
          "fetch_total" : 201041,
          "fetch_time_in_millis" : 627043,
          "fetch_current" : 0,
          "scroll_total" : 380,
          "scroll_time_in_millis" : 50711154,
          "scroll_current" : 0,
          "suggest_total" : 0,
          "suggest_time_in_millis" : 0,
          "suggest_current" : 0
        },
        "merges" : {
          "current" : 0,
          "current_docs" : 0,
          "current_size_in_bytes" : 0,
          "total" : 11120,
          "total_time_in_millis" : 1244347,
          "total_docs" : 19291833,
          "total_size_in_bytes" : 24989144819,
          "total_stopped_time_in_millis" : 0,
          "total_throttled_time_in_millis" : 22811,
          "total_auto_throttle_in_bytes" : 1312350767
        },
        "refresh" : {
          "total" : 110796,
          "total_time_in_millis" : 2457777,
          "listeners" : 0
        },
        "flush" : {
          "total" : 519,
          "periodic" : 0,
          "total_time_in_millis" : 10168
        },
        "warmer" : {
          "current" : 0,
          "total" : 109671,
          "total_time_in_millis" : 5917
        },
        "query_cache" : {
          "memory_size_in_bytes" : 35766313,
          "total_count" : 4976791,
          "hit_count" : 270673,
          "miss_count" : 4706118,
          "cache_size" : 16465,
          "cache_count" : 16469,
          "evictions" : 4
        },
        "fielddata" : {
          "memory_size_in_bytes" : 47157316,
          "evictions" : 0
        },
        "completion" : {
          "size_in_bytes" : 0
        },
        "segments" : {
          "count" : 630,
          "memory_in_bytes" : 76169273,
          "terms_memory_in_bytes" : 63467957,
          "stored_fields_memory_in_bytes" : 7483432,
          "term_vectors_memory_in_bytes" : 0,
          "norms_memory_in_bytes" : 2620224,
          "points_memory_in_bytes" : 589628,
          "doc_values_memory_in_bytes" : 2008032,
          "index_writer_memory_in_bytes" : 0,
          "version_map_memory_in_bytes" : 174,
          "fixed_bit_set_memory_in_bytes" : 0,
          "max_unsafe_auto_id_timestamp" : 1550721329971,
          "file_sizes" : { }
        },
        "translog" : {
          "operations" : 42632,
          "size_in_bytes" : 283805246,
          "uncommitted_operations" : 41476,
          "uncommitted_size_in_bytes" : 273971860,
          "earliest_last_modified_age" : 0
        },
        "request_cache" : {
          "memory_size_in_bytes" : 42336284,
          "evictions" : 0,
          "hit_count" : 162917,
          "miss_count" : 67437
        },
        "recovery" : {
          "current_as_source" : 0,
          "current_as_target" : 0,
          "throttle_time_in_millis" : 1422974
        }
      },
      "os" : {
        "timestamp" : 1552076357548,
        "cpu" : {
          "percent" : 1,
          "load_average" : {
            "1m" : 0.0,
            "5m" : 0.06,
            "15m" : 0.12
          }
        },
        "mem" : {
          "total_in_bytes" : 65842671616,
          "free_in_bytes" : 454729728,
          "used_in_bytes" : 65387941888,
          "free_percent" : 1,
          "used_percent" : 99
        },
        "swap" : {
          "total_in_bytes" : 0,
          "free_in_bytes" : 0,
          "used_in_bytes" : 0
        },
        "cgroup" : {
          "cpuacct" : {
            "control_group" : "/",
            "usage_nanos" : 34654438025458
          },
          "cpu" : {
            "control_group" : "/",
            "cfs_period_micros" : 100000,
            "cfs_quota_micros" : -1,
            "stat" : {
              "number_of_elapsed_periods" : 0,
              "number_of_times_throttled" : 0,
              "time_throttled_nanos" : 0
            }
          },
          "memory" : {
            "control_group" : "/system.slice/elasticsearch.service",
            "limit_in_bytes" : "9223372036854771712",
            "usage_in_bytes" : "28166864896"
          }
        }
      },
      "process" : {
        "timestamp" : 1552076357548,
        "open_file_descriptors" : 894,
        "max_file_descriptors" : 65536,
        "cpu" : {
          "percent" : 1,
          "total_in_millis" : 16177410
        },
        "mem" : {
          "total_virtual_in_bytes" : 82807570432
        }
      },
      "jvm" : {
        "timestamp" : 1552076357548,
        "uptime_in_millis" : 180119748,
        "mem" : {
          "heap_used_in_bytes" : 6879462840,
          "heap_used_percent" : 21,
          "heap_committed_in_bytes" : 32098877440,
          "heap_max_in_bytes" : 32098877440,
          "non_heap_used_in_bytes" : 209651472,
          "non_heap_committed_in_bytes" : 221859840,
          "pools" : {
            "young" : {
              "used_in_bytes" : 535951304,
              "max_in_bytes" : 907345920,
              "peak_used_in_bytes" : 907345920,
              "peak_max_in_bytes" : 907345920
            },
            "survivor" : {
              "used_in_bytes" : 15265400,
              "max_in_bytes" : 113377280,
              "peak_used_in_bytes" : 113377280,
              "peak_max_in_bytes" : 113377280
            },
            "old" : {
              "used_in_bytes" : 6328246136,
              "max_in_bytes" : 31078154240,
              "peak_used_in_bytes" : 6328246136,
              "peak_max_in_bytes" : 31078154240
            }
          }
        },
        "threads" : {
          "count" : 199,
          "peak_count" : 204
        },
        "gc" : {
          "collectors" : {
            "young" : {
              "collection_count" : 18768,
              "collection_time_in_millis" : 695202
            },
            "old" : {
              "collection_count" : 2,
              "collection_time_in_millis" : 136
            }
          }
        },
        "buffer_pools" : {
          "direct" : {
            "count" : 252,
            "used_in_bytes" : 541705015,
            "total_capacity_in_bytes" : 541705014
          },
          "mapped" : {
            "count" : 1222,
            "used_in_bytes" : 38988059022,
            "total_capacity_in_bytes" : 38988059022
          }
        },
        "classes" : {
          "current_loaded_count" : 19901,
          "total_loaded_count" : 19901,
          "total_unloaded_count" : 0
        }
      },
      "thread_pool" : {
        "analyze" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "fetch_shard_started" : {
          "threads" : 1,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 6,
          "completed" : 131
        },
        "fetch_shard_store" : {
          "threads" : 1,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 19,
          "completed" : 131
        },
        "flush" : {
          "threads" : 1,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 4,
          "completed" : 1022
        },
        "force_merge" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "generic" : {
          "threads" : 8,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 8,
          "completed" : 601999
        },
        "get" : {
          "threads" : 16,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 16,
          "completed" : 79571
        },
        "index" : {
          "threads" : 16,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 16,
          "completed" : 865
        },
        "listener" : {
          "threads" : 8,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 8,
          "completed" : 37
        },
        "management" : {
          "threads" : 4,
          "queue" : 0,
          "active" : 1,
          "rejected" : 0,
          "largest" : 4,
          "completed" : 458439
        },
        "ml_autodetect" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "ml_datafeed" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "ml_utility" : {
          "threads" : 12,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 12,
          "completed" : 12
        },
        "refresh" : {
          "threads" : 8,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 8,
          "completed" : 5184592
        },
        "rollup_indexing" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "search" : {
          "threads" : 25,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 25,
          "completed" : 3737851
        },
        "security-token-key" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "snapshot" : {
          "threads" : 1,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 5,
          "completed" : 77
        },
        "warmer" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "watcher" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "write" : {
          "threads" : 16,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 16,
          "completed" : 151479
        }
      },
      "fs" : {
        "timestamp" : 1552076357550,
        "total" : {
          "total_in_bytes" : 1056755048448,
          "free_in_bytes" : 1016886763520,
          "available_in_bytes" : 963182895104
        },
        "least_usage_estimate" : {
          "path" : "/opt/mount/var/data/myapp/elasticsearch/nodes/0",
          "total_in_bytes" : 1056755048448,
          "available_in_bytes" : 963183337472,
          "used_disk_percent" : 8.854626350110536
        },
        "most_usage_estimate" : {
          "path" : "/opt/mount/var/data/myapp/elasticsearch/nodes/0",
          "total_in_bytes" : 1056755048448,
          "available_in_bytes" : 963183337472,
          "used_disk_percent" : 8.854626350110536
        },
        "data" : [
          {
            "path" : "/opt/mount/var/data/myapp/elasticsearch/nodes/0",
            "mount" : "/opt/mount (/dev/nvme1n1)",
            "type" : "ext4",
            "total_in_bytes" : 1056755048448,
            "free_in_bytes" : 1016886763520,
            "available_in_bytes" : 963182895104
          }
        ],
        "io_stats" : {
          "devices" : [
            {
              "device_name" : "nvme1n1",
              "operations" : 3140352,
              "read_operations" : 1032024,
              "write_operations" : 2108328,
              "read_kilobytes" : 7434064,
              "write_kilobytes" : 77954812
            }
          ],
          "total" : {
            "operations" : 3140352,
            "read_operations" : 1032024,
            "write_operations" : 2108328,
            "read_kilobytes" : 7434064,
            "write_kilobytes" : 77954812
          }
        }
      },
      "transport" : {
        "server_open" : 72,
        "rx_count" : 10221164,
        "rx_size_in_bytes" : 26599343356,
        "tx_count" : 10221163,
        "tx_size_in_bytes" : 32585323282
      },
      "http" : {
        "current_open" : 0,
        "total_opened" : 0
      },
      "breakers" : {
        "request" : {
          "limit_size_in_bytes" : 19259326464,
          "limit_size" : "17.9gb",
          "estimated_size_in_bytes" : 0,
          "estimated_size" : "0b",
          "overhead" : 1.0,
          "tripped" : 0
        },
        "fielddata" : {
          "limit_size_in_bytes" : 19259326464,
          "limit_size" : "17.9gb",
          "estimated_size_in_bytes" : 47157316,
          "estimated_size" : "44.9mb",
          "overhead" : 1.03,
          "tripped" : 0
        },
        "in_flight_requests" : {
          "limit_size_in_bytes" : 32098877440,
          "limit_size" : "29.8gb",
          "estimated_size_in_bytes" : 2041,
          "estimated_size" : "1.9kb",
          "overhead" : 1.0,
          "tripped" : 0
        },
        "accounting" : {
          "limit_size_in_bytes" : 32098877440,
          "limit_size" : "29.8gb",
          "estimated_size_in_bytes" : 76169273,
          "estimated_size" : "72.6mb",
          "overhead" : 1.0,
          "tripped" : 0
        },
        "parent" : {
          "limit_size_in_bytes" : 22469214208,
          "limit_size" : "20.9gb",
          "estimated_size_in_bytes" : 123328630,
          "estimated_size" : "117.6mb",
          "overhead" : 1.0,
          "tripped" : 0
        }
      },
      "script" : {
        "compilations" : 6,
        "cache_evictions" : 0
      },
      "discovery" : {
        "cluster_state_queue" : {
          "total" : 0,
          "pending" : 0,
          "committed" : 0
        },
        "published_cluster_states" : {
          "full_states" : 0,
          "incompatible_diffs" : 0,
          "compatible_diffs" : 0
        }
      },
      "ingest" : {
        "total" : {
          "count" : 0,
          "time_in_millis" : 0,
          "current" : 0,
          "failed" : 0
        },
        "pipelines" : {
          "xpack_monitoring_6" : {
            "count" : 0,
            "time_in_millis" : 0,
            "current" : 0,
            "failed" : 0
          },
          "xpack_monitoring_2" : {
            "count" : 0,
            "time_in_millis" : 0,
            "current" : 0,
            "failed" : 0
          }
        }
      },
      "adaptive_selection" : { }
    },
    "TWhObn_IQNexkw7FZs88xg" : {
      "timestamp" : 1552076357462,
      "name" : "ip-10-200-182-76.kdc.capitalone.com",
      "transport_address" : "10.200.182.76:9300",
      "host" : "10.200.182.76",
      "ip" : "10.200.182.76:9300",
      "roles" : [ ],
      "attributes" : {
        "aws_availability_zone" : "us-east-1c",
        "ml.machine_memory" : "16170369024",
        "ml.max_open_jobs" : "20",
        "xpack.installed" : "true",
        "ml.enabled" : "true"
      },
      "indices" : {
        "docs" : {
          "count" : 0,
          "deleted" : 0
        },
        "store" : {
          "size_in_bytes" : 0
        },
        "indexing" : {
          "index_total" : 0,
          "index_time_in_millis" : 0,
          "index_current" : 0,
          "index_failed" : 0,
          "delete_total" : 0,
          "delete_time_in_millis" : 0,
          "delete_current" : 0,
          "noop_update_total" : 0,
          "is_throttled" : false,
          "throttle_time_in_millis" : 0
        },
        "get" : {
          "total" : 0,
          "time_in_millis" : 0,
          "exists_total" : 0,
          "exists_time_in_millis" : 0,
          "missing_total" : 0,
          "missing_time_in_millis" : 0,
          "current" : 0
        },
        "search" : {
          "open_contexts" : 0,
          "query_total" : 0,
          "query_time_in_millis" : 0,
          "query_current" : 0,
          "fetch_total" : 0,
          "fetch_time_in_millis" : 0,
          "fetch_current" : 0,
          "scroll_total" : 0,
          "scroll_time_in_millis" : 0,
          "scroll_current" : 0,
          "suggest_total" : 0,
          "suggest_time_in_millis" : 0,
          "suggest_current" : 0
        },
        "merges" : {
          "current" : 0,
          "current_docs" : 0,
          "current_size_in_bytes" : 0,
          "total" : 0,
          "total_time_in_millis" : 0,
          "total_docs" : 0,
          "total_size_in_bytes" : 0,
          "total_stopped_time_in_millis" : 0,
          "total_throttled_time_in_millis" : 0,
          "total_auto_throttle_in_bytes" : 0
        },
        "refresh" : {
          "total" : 0,
          "total_time_in_millis" : 0,
          "listeners" : 0
        },
        "flush" : {
          "total" : 0,
          "periodic" : 0,
          "total_time_in_millis" : 0
        },
        "warmer" : {
          "current" : 0,
          "total" : 0,
          "total_time_in_millis" : 0
        },
        "query_cache" : {
          "memory_size_in_bytes" : 0,
          "total_count" : 0,
          "hit_count" : 0,
          "miss_count" : 0,
          "cache_size" : 0,
          "cache_count" : 0,
          "evictions" : 0
        },
        "fielddata" : {
          "memory_size_in_bytes" : 0,
          "evictions" : 0
        },
        "completion" : {
          "size_in_bytes" : 0
        },
        "segments" : {
          "count" : 0,
          "memory_in_bytes" : 0,
          "terms_memory_in_bytes" : 0,
          "stored_fields_memory_in_bytes" : 0,
          "term_vectors_memory_in_bytes" : 0,
          "norms_memory_in_bytes" : 0,
          "points_memory_in_bytes" : 0,
          "doc_values_memory_in_bytes" : 0,
          "index_writer_memory_in_bytes" : 0,
          "version_map_memory_in_bytes" : 0,
          "fixed_bit_set_memory_in_bytes" : 0,
          "max_unsafe_auto_id_timestamp" : -9223372036854775808,
          "file_sizes" : { }
        },
        "translog" : {
          "operations" : 0,
          "size_in_bytes" : 0,
          "uncommitted_operations" : 0,
          "uncommitted_size_in_bytes" : 0,
          "earliest_last_modified_age" : 0
        },
        "request_cache" : {
          "memory_size_in_bytes" : 0,
          "evictions" : 0,
          "hit_count" : 0,
          "miss_count" : 0
        },
        "recovery" : {
          "current_as_source" : 0,
          "current_as_target" : 0,
          "throttle_time_in_millis" : 0
        }
      },
      "os" : {
        "timestamp" : 1552076357464,
        "cpu" : {
          "percent" : 3,
          "load_average" : {
            "1m" : 0.1,
            "5m" : 0.04,
            "15m" : 0.05
          }
        },
        "mem" : {
          "total_in_bytes" : 16170369024,
          "free_in_bytes" : 3700469760,
          "used_in_bytes" : 12469899264,
          "free_percent" : 23,
          "used_percent" : 77
        },
        "swap" : {
          "total_in_bytes" : 0,
          "free_in_bytes" : 0,
          "used_in_bytes" : 0
        },
        "cgroup" : {
          "cpuacct" : {
            "control_group" : "/",
            "usage_nanos" : 21850007339918
          },
          "cpu" : {
            "control_group" : "/",
            "cfs_period_micros" : 100000,
            "cfs_quota_micros" : -1,
            "stat" : {
              "number_of_elapsed_periods" : 0,
              "number_of_times_throttled" : 0,
              "time_throttled_nanos" : 0
            }
          },
          "memory" : {
            "control_group" : "/system.slice/elasticsearch.service",
            "limit_in_bytes" : "9223372036854771712",
            "usage_in_bytes" : "1100759040"
          }
        }
      },
      "process" : {
        "timestamp" : 1552076357464,
        "open_file_descriptors" : 508,
        "max_file_descriptors" : 65536,
        "cpu" : {
          "percent" : 1,
          "total_in_millis" : 3411250
        },
        "mem" : {
          "total_virtual_in_bytes" : 12296945664
        }
      },
      "jvm" : {
        "timestamp" : 1552076357464,
        "uptime_in_millis" : 179903820,
        "mem" : {
          "heap_used_in_bytes" : 4792304512,
          "heap_used_percent" : 64,
          "heap_committed_in_bytes" : 7481327616,
          "heap_max_in_bytes" : 7481327616,
          "non_heap_used_in_bytes" : 148216824,
          "non_heap_committed_in_bytes" : 158662656,
          "pools" : {
            "young" : {
              "used_in_bytes" : 100821352,
              "max_in_bytes" : 279183360,
              "peak_used_in_bytes" : 279183360,
              "peak_max_in_bytes" : 279183360
            },
            "survivor" : {
              "used_in_bytes" : 1390792,
              "max_in_bytes" : 34865152,
              "peak_used_in_bytes" : 34865152,
              "peak_max_in_bytes" : 34865152
            },
            "old" : {
              "used_in_bytes" : 4690092368,
              "max_in_bytes" : 7167279104,
              "peak_used_in_bytes" : 5384956984,
              "peak_max_in_bytes" : 7167279104
            }
          }
        },
        "threads" : {
          "count" : 59,
          "peak_count" : 63
        },
        "gc" : {
          "collectors" : {
            "young" : {
              "collection_count" : 2140,
              "collection_time_in_millis" : 36105
            },
            "old" : {
              "collection_count" : 3,
              "collection_time_in_millis" : 177
            }
          }
        },
        "buffer_pools" : {
          "direct" : {
            "count" : 50,
            "used_in_bytes" : 773177664,
            "total_capacity_in_bytes" : 773177662
          },
          "mapped" : {
            "count" : 0,
            "used_in_bytes" : 0,
            "total_capacity_in_bytes" : 0
          }
        },
        "classes" : {
          "current_loaded_count" : 17684,
          "total_loaded_count" : 17847,
          "total_unloaded_count" : 163
        }
      },
      "thread_pool" : {
        "analyze" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "fetch_shard_started" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "fetch_shard_store" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "flush" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "force_merge" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "generic" : {
          "threads" : 6,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 6,
          "completed" : 593298
        },
        "get" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "index" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "listener" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "management" : {
          "threads" : 5,
          "queue" : 0,
          "active" : 1,
          "rejected" : 0,
          "largest" : 5,
          "completed" : 441919
        },
        "ml_autodetect" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "ml_datafeed" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "ml_utility" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "refresh" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "rollup_indexing" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "search" : {
          "threads" : 7,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 7,
          "completed" : 2176232
        },
        "snapshot" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "warmer" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "watcher" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        },
        "write" : {
          "threads" : 0,
          "queue" : 0,
          "active" : 0,
          "rejected" : 0,
          "largest" : 0,
          "completed" : 0
        }
      },
      "fs" : {
        "timestamp" : 1552076357466,
        "total" : {
          "total_in_bytes" : 52710309888,
          "free_in_bytes" : 52629098496,
          "available_in_bytes" : 49927966720
        },
        "data" : [
          {
            "path" : "/opt/mount/var/data/myapp/elasticsearch/nodes/0",
            "mount" : "/opt/mount (/dev/nvme1n1)",
            "type" : "ext4",
            "total_in_bytes" : 52710309888,
            "free_in_bytes" : 52629098496,
            "available_in_bytes" : 49927966720
          }
        ],
        "io_stats" : {
          "devices" : [
            {
              "device_name" : "nvme1n1",
              "operations" : 58041,
              "read_operations" : 3,
              "write_operations" : 58038,
              "read_kilobytes" : 56,
              "write_kilobytes" : 363352
            }
          ],
          "total" : {
            "operations" : 58041,
            "read_operations" : 3,
            "write_operations" : 58038,
            "read_kilobytes" : 56,
            "write_kilobytes" : 363352
          }
        }
      },
      "transport" : {
        "server_open" : 75,
        "rx_count" : 18714596,
        "rx_size_in_bytes" : 25192475225,
        "tx_count" : 18714595,
        "tx_size_in_bytes" : 10958660721
      },
      "http" : {
        "current_open" : 70,
        "total_opened" : 325138
      },
      "breakers" : {
        "request" : {
          "limit_size_in_bytes" : 4488796569,
          "limit_size" : "4.1gb",
          "estimated_size_in_bytes" : 0,
          "estimated_size" : "0b",
          "overhead" : 1.0,
          "tripped" : 0
        },
        "fielddata" : {
          "limit_size_in_bytes" : 4488796569,
          "limit_size" : "4.1gb",
          "estimated_size_in_bytes" : 0,
          "estimated_size" : "0b",
          "overhead" : 1.03,
          "tripped" : 0
        },
        "in_flight_requests" : {
          "limit_size_in_bytes" : 7481327616,
          "limit_size" : "6.9gb",
          "estimated_size_in_bytes" : 2041,
          "estimated_size" : "1.9kb",
          "overhead" : 1.0,
          "tripped" : 0
        },
        "accounting" : {
          "limit_size_in_bytes" : 7481327616,
          "limit_size" : "6.9gb",
          "estimated_size_in_bytes" : 0,
          "estimated_size" : "0b",
          "overhead" : 1.0,
          "tripped" : 0
        },
        "parent" : {
          "limit_size_in_bytes" : 5236929331,
          "limit_size" : "4.8gb",
          "estimated_size_in_bytes" : 2041,
          "estimated_size" : "1.9kb",
          "overhead" : 1.0,
          "tripped" : 0
        }
      },
      "script" : {
        "compilations" : 6,
        "cache_evictions" : 0
      },
      "discovery" : {
        "cluster_state_queue" : {
          "total" : 0,
          "pending" : 0,
          "committed" : 0
        },
        "published_cluster_states" : {
          "full_states" : 1,
          "incompatible_diffs" : 0,
          "compatible_diffs" : 650
        }
      },
      "ingest" : {
        "total" : {
          "count" : 0,
          "time_in_millis" : 0,
          "current" : 0,
          "failed" : 0
        },
        "pipelines" : {
          "xpack_monitoring_2" : {
            "count" : 0,
            "time_in_millis" : 0,
            "current" : 0,
            "failed" : 0
          },
          "xpack_monitoring_6" : {
            "count" : 0,
            "time_in_millis" : 0,
            "current" : 0,
            "failed" : 0
          }
        }
      },
      "adaptive_selection" : {
        "OWya11Y4T4y2BfRMURk0wA" : {
          "outgoing_searches" : 0,
          "avg_queue_size" : 0,
          "avg_service_time_ns" : 218144,
          "avg_response_time_ns" : 1138835,
          "rank" : "1.1"
        },
        "DZDySdQ-TNqWcxXBd1XAGQ" : {
          "outgoing_searches" : 0,
          "avg_queue_size" : 0,
          "avg_service_time_ns" : 591500,
          "avg_response_time_ns" : 1533185,
          "rank" : "1.5"
        },
        "f492qWFDQyG8fkxNwf9mfQ" : {
          "outgoing_searches" : 0,
          "avg_queue_size" : 0,
          "avg_service_time_ns" : 174109,
          "avg_response_time_ns" : 682223,
          "rank" : "0.7"
        },
        "zhMmgMtsRCGK5AgAR1_Vmw" : {
          "outgoing_searches" : 0,
          "avg_queue_size" : 0,
          "avg_service_time_ns" : 172703,
          "avg_response_time_ns" : 1331901,
          "rank" : "1.3"
        },
        "TLp5t8ZGTWqSP4WTmzGcVg" : {
          "outgoing_searches" : 0,
          "avg_queue_size" : 0,
          "avg_service_time_ns" : 1224227,
          "avg_response_time_ns" : 1124305,
          "rank" : "1.1"
        }
      }
    }
  }
}
