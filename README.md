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

# Server Metrics 2026-03-18 07:13:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 131279.1 (36h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1743942
telemt_connections_bad_total 11623
telemt_handshake_timeouts_total 37194
telemt_upstream_connect_attempt_total 28431
telemt_upstream_connect_success_total 27908
telemt_upstream_connect_fail_total 523
telemt_upstream_connect_attempts_per_request{bucket="1"} 28431
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14268
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13432
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 523
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 286
telemt_me_reconnect_attempts_total 36257
telemt_me_reconnect_success_total 19096
telemt_me_reader_eof_total 20680
telemt_me_idle_close_by_peer_total 20679
telemt_me_route_drop_no_conn_total 651641
telemt_me_route_drop_channel_closed_total 187
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1429330
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8601
telemt_desync_full_logged_total 2603
telemt_desync_suppressed_total 5998
telemt_desync_frames_bucket_total{bucket="1_2"} 2219
telemt_desync_frames_bucket_total{bucket="3_10"} 3322
telemt_desync_frames_bucket_total{bucket="gt_10"} 3060
telemt_pool_swap_total 111
telemt_me_writer_removed_unexpected_total 19918
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 19074
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 822
telemt_user_connections_total{user="hello"} 1423586
telemt_user_connections_current{user="hello"} 1279
telemt_user_octets_from_client{user="hello"} 32997314735 (30.73 GB)
telemt_user_octets_to_client{user="hello"} 508261592811 (473.36 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 427
telemt_user_unique_ips_recent_window{user="hello"} 200
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 131530.5 (36h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1835130
telemt_connections_bad_total 94845
telemt_handshake_timeouts_total 58294
telemt_upstream_connect_attempt_total 472044
telemt_upstream_connect_success_total 470394
telemt_upstream_connect_fail_total 1650
telemt_upstream_connect_attempts_per_request{bucket="1"} 472044
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 391679
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35344
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43369
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1650
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 411
telemt_me_reconnect_attempts_total 129026
telemt_me_reconnect_success_total 20915
telemt_me_reader_eof_total 23274
telemt_me_idle_close_by_peer_total 23261
telemt_me_route_drop_no_conn_total 511109
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1153401
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5272
telemt_desync_full_logged_total 1844
telemt_desync_suppressed_total 3428
telemt_desync_frames_bucket_total{bucket="1_2"} 991
telemt_desync_frames_bucket_total{bucket="3_10"} 2141
telemt_desync_frames_bucket_total{bucket="gt_10"} 2140
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 22597
telemt_me_refill_failed_total 3372
telemt_me_writer_restored_same_endpoint_total 20897
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1682
telemt_user_connections_total{user="hello"} 1595751
telemt_user_connections_current{user="hello"} 2480
telemt_user_octets_from_client{user="hello"} 24644746773 (22.95 GB)
telemt_user_octets_to_client{user="hello"} 627343422654 (584.26 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 779
telemt_user_unique_ips_recent_window{user="hello"} 334
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 131306.5 (36h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1339182
telemt_connections_bad_total 84601
telemt_handshake_timeouts_total 32472
telemt_upstream_connect_attempt_total 29673
telemt_upstream_connect_success_total 29507
telemt_upstream_connect_fail_total 166
telemt_upstream_connect_attempts_per_request{bucket="1"} 29673
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13608
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15797
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 166
telemt_me_keepalive_timeout_total 162
telemt_me_reconnect_attempts_total 43652
telemt_me_reconnect_success_total 22934
telemt_me_reader_eof_total 24904
telemt_me_idle_close_by_peer_total 24896
telemt_me_route_drop_no_conn_total 502686
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 994107
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3500
telemt_desync_full_logged_total 1149
telemt_desync_suppressed_total 2351
telemt_desync_frames_bucket_total{bucket="1_2"} 946
telemt_desync_frames_bucket_total{bucket="3_10"} 1345
telemt_desync_frames_bucket_total{bucket="gt_10"} 1209
telemt_pool_swap_total 109
telemt_me_writer_removed_unexpected_total 23901
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 22922
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 967
telemt_user_connections_total{user="hello"} 992141
telemt_user_connections_current{user="hello"} 1563
telemt_user_octets_from_client{user="hello"} 49013302692 (45.65 GB)
telemt_user_octets_to_client{user="hello"} 479478318948 (446.55 GB)
telemt_user_unique_ips_current{user="hello"} 511
telemt_user_unique_ips_recent_window{user="hello"} 221
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 131365.8 (36h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1726545
telemt_connections_bad_total 85195
telemt_handshake_timeouts_total 30686
telemt_upstream_connect_attempt_total 92787
telemt_upstream_connect_success_total 90332
telemt_upstream_connect_fail_total 2455
telemt_upstream_connect_attempts_per_request{bucket="1"} 92787
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74388
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15524
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 387
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2455
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 350
telemt_me_reconnect_attempts_total 39472
telemt_me_reconnect_success_total 19043
telemt_me_reader_eof_total 20847
telemt_me_idle_close_by_peer_total 20844
telemt_me_route_drop_no_conn_total 706458
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1424123
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5527
telemt_desync_full_logged_total 1753
telemt_desync_suppressed_total 3774
telemt_desync_frames_bucket_total{bucket="1_2"} 1295
telemt_desync_frames_bucket_total{bucket="3_10"} 2259
telemt_desync_frames_bucket_total{bucket="gt_10"} 1973
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 20035
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 19023
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 992
telemt_user_connections_total{user="hello"} 1487318
telemt_user_connections_current{user="hello"} 2318
telemt_user_octets_from_client{user="hello"} 24461080450 (22.78 GB)
telemt_user_octets_to_client{user="hello"} 700467063322 (652.36 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 648
telemt_user_unique_ips_recent_window{user="hello"} 283
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 131337.7 (36h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1248627
telemt_connections_bad_total 111828
telemt_handshake_timeouts_total 13339
telemt_upstream_connect_attempt_total 49749
telemt_upstream_connect_success_total 49062
telemt_upstream_connect_fail_total 687
telemt_upstream_connect_attempts_per_request{bucket="1"} 49749
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30197
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18433
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 432
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 687
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 63568
telemt_me_reconnect_success_total 26066
telemt_me_reader_eof_total 28231
telemt_me_idle_close_by_peer_total 28228
telemt_me_route_drop_no_conn_total 413328
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1029887
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4456
telemt_desync_full_logged_total 1382
telemt_desync_suppressed_total 3074
telemt_desync_frames_bucket_total{bucket="1_2"} 1178
telemt_desync_frames_bucket_total{bucket="3_10"} 1721
telemt_desync_frames_bucket_total{bucket="gt_10"} 1557
telemt_pool_swap_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 27642
telemt_me_refill_failed_total 1166
telemt_me_writer_restored_same_endpoint_total 26058
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1576
telemt_user_connections_total{user="hello"} 1046249
telemt_user_connections_current{user="hello"} 2054
telemt_user_octets_from_client{user="hello"} 20663918296 (19.24 GB)
telemt_user_octets_to_client{user="hello"} 523787937152 (487.82 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 620
telemt_user_unique_ips_recent_window{user="hello"} 274
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 131498.9 (36h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1284136
telemt_connections_bad_total 134027
telemt_handshake_timeouts_total 10933
telemt_upstream_connect_attempt_total 26236
telemt_upstream_connect_success_total 26079
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 26235
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12558
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13398
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 113
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_keepalive_timeout_total 269
telemt_me_reconnect_attempts_total 30834
telemt_me_reconnect_success_total 19531
telemt_me_reader_eof_total 21120
telemt_me_idle_close_by_peer_total 21117
telemt_me_route_drop_no_conn_total 853612
telemt_me_route_drop_channel_closed_total 96
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1252908
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2465
telemt_desync_full_logged_total 866
telemt_desync_suppressed_total 1599
telemt_desync_frames_bucket_total{bucket="1_2"} 546
telemt_desync_frames_bucket_total{bucket="3_10"} 949
telemt_desync_frames_bucket_total{bucket="gt_10"} 970
telemt_pool_swap_total 118
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 20181
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 19517
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 650
telemt_user_connections_total{user="hello"} 1061560
telemt_user_connections_current{user="hello"} 903
telemt_user_octets_from_client{user="hello"} 16548806576 (15.41 GB)
telemt_user_octets_to_client{user="hello"} 468180022000 (436.03 GB)
telemt_user_unique_ips_current{user="hello"} 287
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 79265.9 (22h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 705039
telemt_connections_bad_total 61995
telemt_handshake_timeouts_total 15182
telemt_upstream_connect_attempt_total 26647
telemt_upstream_connect_success_total 26366
telemt_upstream_connect_fail_total 281
telemt_upstream_connect_attempts_per_request{bucket="1"} 26647
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14053
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12212
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 281
telemt_me_keepalive_timeout_total 149
telemt_me_reconnect_attempts_total 33904
telemt_me_reconnect_success_total 22284
telemt_me_reader_eof_total 23546
telemt_me_idle_close_by_peer_total 23546
telemt_me_seq_mismatch_total 37
telemt_me_route_drop_no_conn_total 201959
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 531701
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 41
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2235
telemt_desync_full_logged_total 766
telemt_desync_suppressed_total 1469
telemt_desync_frames_bucket_total{bucket="1_2"} 373
telemt_desync_frames_bucket_total{bucket="3_10"} 957
telemt_desync_frames_bucket_total{bucket="gt_10"} 905
telemt_pool_swap_total 56
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22888
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 22237
telemt_me_writer_restored_fallback_total 47
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 604
telemt_user_connections_total{user="hello"} 531402
telemt_user_connections_current{user="hello"} 1543
telemt_user_octets_from_client{user="hello"} 28203919317 (26.27 GB)
telemt_user_octets_to_client{user="hello"} 389219523310 (362.49 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 460
telemt_user_unique_ips_recent_window{user="hello"} 185
```