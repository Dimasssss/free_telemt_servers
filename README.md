# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-40
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 639 RUB
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s3.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## landvps.ru
- Локация: Финляндия
- Тариф: FL-2
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 200 Mbps/s
- Цена в месяц: 800 RUB
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s4.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## rdp-onedash.ru
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-17 20:51:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 93989.8 (26h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1160531
telemt_connections_bad_total 8633
telemt_handshake_timeouts_total 30550
telemt_upstream_connect_attempt_total 21443
telemt_upstream_connect_success_total 20953
telemt_upstream_connect_fail_total 490
telemt_upstream_connect_attempts_per_request{bucket="1"} 21443
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10844
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9902
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 207
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 490
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 31075
telemt_me_reconnect_success_total 13945
telemt_me_reader_eof_total 15162
telemt_me_idle_close_by_peer_total 15161
telemt_me_route_drop_no_conn_total 518909
telemt_me_route_drop_channel_closed_total 153
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1064006
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7090
telemt_desync_full_logged_total 2032
telemt_desync_suppressed_total 5058
telemt_desync_frames_bucket_total{bucket="1_2"} 1910
telemt_desync_frames_bucket_total{bucket="3_10"} 2686
telemt_desync_frames_bucket_total{bucket="gt_10"} 2494
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 14686
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 13923
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 741
telemt_user_connections_total{user="hello"} 1058242
telemt_user_connections_current{user="hello"} 684
telemt_user_octets_from_client{user="hello"} 18940602223 (17.64 GB)
telemt_user_octets_to_client{user="hello"} 371669320103 (346.14 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 259
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 94241.1 (26h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1193952
telemt_connections_bad_total 59445
telemt_handshake_timeouts_total 42909
telemt_upstream_connect_attempt_total 456957
telemt_upstream_connect_success_total 456073
telemt_upstream_connect_fail_total 884
telemt_upstream_connect_attempts_per_request{bucket="1"} 456957
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 382551
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30231
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43289
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 884
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 57514
telemt_me_reconnect_success_total 14361
telemt_me_reader_eof_total 16315
telemt_me_idle_close_by_peer_total 16315
telemt_me_route_drop_no_conn_total 301490
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 592284
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2574
telemt_desync_full_logged_total 830
telemt_desync_suppressed_total 1744
telemt_desync_frames_bucket_total{bucket="1_2"} 496
telemt_desync_frames_bucket_total{bucket="3_10"} 1075
telemt_desync_frames_bucket_total{bucket="gt_10"} 1003
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 15887
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 14345
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1526
telemt_user_connections_total{user="hello"} 1028712
telemt_user_connections_current{user="hello"} 1252
telemt_user_octets_from_client{user="hello"} 14283711362 (13.30 GB)
telemt_user_octets_to_client{user="hello"} 337826021986 (314.63 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 399
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 94017.3 (26h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 663039
telemt_connections_bad_total 38090
telemt_handshake_timeouts_total 22352
telemt_upstream_connect_attempt_total 22609
telemt_upstream_connect_success_total 22479
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 22609
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10278
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12107
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 38395
telemt_me_reconnect_success_total 17721
telemt_me_reader_eof_total 19343
telemt_me_idle_close_by_peer_total 19336
telemt_me_route_drop_no_conn_total 283096
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 571136
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1812
telemt_desync_full_logged_total 542
telemt_desync_suppressed_total 1270
telemt_desync_frames_bucket_total{bucket="1_2"} 510
telemt_desync_frames_bucket_total{bucket="3_10"} 711
telemt_desync_frames_bucket_total{bucket="gt_10"} 591
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 18608
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 17709
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 887
telemt_user_connections_total{user="hello"} 569408
telemt_user_connections_current{user="hello"} 966
telemt_user_octets_from_client{user="hello"} 28549173584 (26.59 GB)
telemt_user_octets_to_client{user="hello"} 236033748308 (219.82 GB)
telemt_user_unique_ips_current{user="hello"} 281
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 94076.4 (26h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1165278
telemt_connections_bad_total 34887
telemt_handshake_timeouts_total 21162
telemt_upstream_connect_attempt_total 82167
telemt_upstream_connect_success_total 81754
telemt_upstream_connect_fail_total 413
telemt_upstream_connect_attempts_per_request{bucket="1"} 82167
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69613
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11773
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 339
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 413
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 33982
telemt_me_reconnect_success_total 13668
telemt_me_reader_eof_total 15065
telemt_me_idle_close_by_peer_total 15064
telemt_me_route_drop_no_conn_total 486122
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 950703
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3270
telemt_desync_full_logged_total 1040
telemt_desync_suppressed_total 2230
telemt_desync_frames_bucket_total{bucket="1_2"} 803
telemt_desync_frames_bucket_total{bucket="3_10"} 1386
telemt_desync_frames_bucket_total{bucket="gt_10"} 1081
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 14556
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 13659
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 888
telemt_user_connections_total{user="hello"} 1013221
telemt_user_connections_current{user="hello"} 1172
telemt_user_octets_from_client{user="hello"} 15122792679 (14.08 GB)
telemt_user_octets_to_client{user="hello"} 418353073109 (389.62 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 339
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 94048.3 (26h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 719927
telemt_connections_bad_total 89943
telemt_handshake_timeouts_total 6134
telemt_upstream_connect_attempt_total 40990
telemt_upstream_connect_success_total 40443
telemt_upstream_connect_fail_total 547
telemt_upstream_connect_attempts_per_request{bucket="1"} 40990
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26078
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13973
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 392
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 547
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 51727
telemt_me_reconnect_success_total 19242
telemt_me_reader_eof_total 20959
telemt_me_idle_close_by_peer_total 20957
telemt_me_route_drop_no_conn_total 224301
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 568616
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2618
telemt_desync_full_logged_total 755
telemt_desync_suppressed_total 1863
telemt_desync_frames_bucket_total{bucket="1_2"} 875
telemt_desync_frames_bucket_total{bucket="3_10"} 1051
telemt_desync_frames_bucket_total{bucket="gt_10"} 692
telemt_pool_swap_total 47
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 20585
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 19234
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1343
telemt_user_connections_total{user="hello"} 585237
telemt_user_connections_current{user="hello"} 1131
telemt_user_octets_from_client{user="hello"} 11506097816 (10.72 GB)
telemt_user_octets_to_client{user="hello"} 280169817040 (260.93 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 345
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 94209.8 (26h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 969527
telemt_connections_bad_total 69098
telemt_handshake_timeouts_total 9208
telemt_upstream_connect_attempt_total 18635
telemt_upstream_connect_success_total 18526
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 18635
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8815
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9595
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 25091
telemt_me_reconnect_success_total 13814
telemt_me_reader_eof_total 15008
telemt_me_idle_close_by_peer_total 15006
telemt_me_route_drop_no_conn_total 677361
telemt_me_route_drop_channel_closed_total 86
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 969722
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1939
telemt_desync_full_logged_total 681
telemt_desync_suppressed_total 1258
telemt_desync_frames_bucket_total{bucket="1_2"} 447
telemt_desync_frames_bucket_total{bucket="3_10"} 737
telemt_desync_frames_bucket_total{bucket="gt_10"} 755
telemt_pool_swap_total 79
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 14395
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 13800
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 581
telemt_user_connections_total{user="hello"} 832756
telemt_user_connections_current{user="hello"} 615
telemt_user_octets_from_client{user="hello"} 12920315948 (12.03 GB)
telemt_user_octets_to_client{user="hello"} 359877685044 (335.16 GB)
telemt_user_unique_ips_current{user="hello"} 214
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 41976.5 (11h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 301181
telemt_connections_bad_total 39864
telemt_handshake_timeouts_total 8863
telemt_upstream_connect_attempt_total 17283
telemt_upstream_connect_success_total 17123
telemt_upstream_connect_fail_total 160
telemt_upstream_connect_attempts_per_request{bucket="1"} 17283
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9182
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7850
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 160
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 26442
telemt_me_reconnect_success_total 14851
telemt_me_reader_eof_total 15693
telemt_me_idle_close_by_peer_total 15693
telemt_me_seq_mismatch_total 20
telemt_me_route_drop_no_conn_total 73967
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 231670
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 706
telemt_desync_full_logged_total 193
telemt_desync_suppressed_total 513
telemt_desync_frames_bucket_total{bucket="1_2"} 187
telemt_desync_frames_bucket_total{bucket="3_10"} 276
telemt_desync_frames_bucket_total{bucket="gt_10"} 243
telemt_pool_swap_total 20
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 15388
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 14823
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 537
telemt_user_connections_total{user="hello"} 231617
telemt_user_connections_current{user="hello"} 683
telemt_user_octets_from_client{user="hello"} 20626168277 (19.21 GB)
telemt_user_octets_to_client{user="hello"} 193459892970 (180.17 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 57
```