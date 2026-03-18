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

# Server Metrics 2026-03-18 03:44:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 118755.9 (32h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1355932
telemt_connections_bad_total 10399
telemt_handshake_timeouts_total 33479
telemt_upstream_connect_attempt_total 26206
telemt_upstream_connect_success_total 25696
telemt_upstream_connect_fail_total 510
telemt_upstream_connect_attempts_per_request{bucket="1"} 26206
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13157
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12331
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 510
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 34653
telemt_me_reconnect_success_total 17509
telemt_me_reader_eof_total 18998
telemt_me_idle_close_by_peer_total 18997
telemt_me_route_drop_no_conn_total 582587
telemt_me_route_drop_channel_closed_total 160
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1248823
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7893
telemt_desync_full_logged_total 2351
telemt_desync_suppressed_total 5542
telemt_desync_frames_bucket_total{bucket="1_2"} 2085
telemt_desync_frames_bucket_total{bucket="3_10"} 3020
telemt_desync_frames_bucket_total{bucket="gt_10"} 2788
telemt_pool_swap_total 100
telemt_me_writer_removed_unexpected_total 18307
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 17487
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 798
telemt_user_connections_total{user="hello"} 1243031
telemt_user_connections_current{user="hello"} 688
telemt_user_octets_from_client{user="hello"} 25178950435 (23.45 GB)
telemt_user_octets_to_client{user="hello"} 441215582599 (410.91 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 287
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 119007.4 (33h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1441849
telemt_connections_bad_total 66347
telemt_handshake_timeouts_total 47933
telemt_upstream_connect_attempt_total 469419
telemt_upstream_connect_success_total 467813
telemt_upstream_connect_fail_total 1606
telemt_upstream_connect_attempts_per_request{bucket="1"} 469419
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 390442
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34009
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43360
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1606
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 125674
telemt_me_reconnect_success_total 18949
telemt_me_reader_eof_total 21189
telemt_me_idle_close_by_peer_total 21176
telemt_me_route_drop_no_conn_total 372107
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 813129
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3733
telemt_desync_full_logged_total 1286
telemt_desync_suppressed_total 2447
telemt_desync_frames_bucket_total{bucket="1_2"} 731
telemt_desync_frames_bucket_total{bucket="3_10"} 1542
telemt_desync_frames_bucket_total{bucket="gt_10"} 1460
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 20565
telemt_me_refill_failed_total 3329
telemt_me_writer_restored_same_endpoint_total 18931
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1616
telemt_user_connections_total{user="hello"} 1255461
telemt_user_connections_current{user="hello"} 983
telemt_user_octets_from_client{user="hello"} 16885599837 (15.73 GB)
telemt_user_octets_to_client{user="hello"} 450215771686 (419.30 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 360
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 118783.4 (32h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 881493
telemt_connections_bad_total 61801
telemt_handshake_timeouts_total 25290
telemt_upstream_connect_attempt_total 27550
telemt_upstream_connect_success_total 27391
telemt_upstream_connect_fail_total 159
telemt_upstream_connect_attempts_per_request{bucket="1"} 27550
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12547
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14744
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 159
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 42147
telemt_me_reconnect_success_total 21451
telemt_me_reader_eof_total 23324
telemt_me_idle_close_by_peer_total 23317
telemt_me_route_drop_no_conn_total 343738
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 741958
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2338
telemt_desync_full_logged_total 761
telemt_desync_suppressed_total 1577
telemt_desync_frames_bucket_total{bucket="1_2"} 672
telemt_desync_frames_bucket_total{bucket="3_10"} 897
telemt_desync_frames_bucket_total{bucket="gt_10"} 769
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 22383
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 21439
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 932
telemt_user_connections_total{user="hello"} 740073
telemt_user_connections_current{user="hello"} 686
telemt_user_octets_from_client{user="hello"} 44529996968 (41.47 GB)
telemt_user_octets_to_client{user="hello"} 334465490460 (311.50 GB)
telemt_user_unique_ips_current{user="hello"} 248
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 118843.0 (33h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1357531
telemt_connections_bad_total 64139
telemt_handshake_timeouts_total 23781
telemt_upstream_connect_attempt_total 90480
telemt_upstream_connect_success_total 88049
telemt_upstream_connect_fail_total 2431
telemt_upstream_connect_attempts_per_request{bucket="1"} 90480
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73203
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14439
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 374
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2431
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 37787
telemt_me_reconnect_success_total 17380
telemt_me_reader_eof_total 19092
telemt_me_idle_close_by_peer_total 19089
telemt_me_route_drop_no_conn_total 554133
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1102369
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4101
telemt_desync_full_logged_total 1353
telemt_desync_suppressed_total 2748
telemt_desync_frames_bucket_total{bucket="1_2"} 1006
telemt_desync_frames_bucket_total{bucket="3_10"} 1714
telemt_desync_frames_bucket_total{bucket="gt_10"} 1381
telemt_pool_swap_total 93
telemt_me_writer_removed_unexpected_total 18341
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 17360
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 961
telemt_user_connections_total{user="hello"} 1165733
telemt_user_connections_current{user="hello"} 854
telemt_user_octets_from_client{user="hello"} 18194592070 (16.95 GB)
telemt_user_octets_to_client{user="hello"} 558069703666 (519.74 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 285
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 118814.6 (33h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 917884
telemt_connections_bad_total 101702
telemt_handshake_timeouts_total 7495
telemt_upstream_connect_attempt_total 47254
telemt_upstream_connect_success_total 46610
telemt_upstream_connect_fail_total 644
telemt_upstream_connect_attempts_per_request{bucket="1"} 47254
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28939
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17254
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 417
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 644
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 59195
telemt_me_reconnect_success_total 24231
telemt_me_reader_eof_total 26250
telemt_me_idle_close_by_peer_total 26247
telemt_me_route_drop_no_conn_total 293073
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 744325
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3360
telemt_desync_full_logged_total 1013
telemt_desync_suppressed_total 2347
telemt_desync_frames_bucket_total{bucket="1_2"} 1036
telemt_desync_frames_bucket_total{bucket="3_10"} 1335
telemt_desync_frames_bucket_total{bucket="gt_10"} 989
telemt_pool_swap_total 62
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 25703
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 24223
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1472
telemt_user_connections_total{user="hello"} 760843
telemt_user_connections_current{user="hello"} 792
telemt_user_octets_from_client{user="hello"} 14515341816 (13.52 GB)
telemt_user_octets_to_client{user="hello"} 377620243748 (351.69 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 300
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 118975.7 (33h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1154763
telemt_connections_bad_total 126844
telemt_handshake_timeouts_total 10214
telemt_upstream_connect_attempt_total 23732
telemt_upstream_connect_success_total 23594
telemt_upstream_connect_fail_total 138
telemt_upstream_connect_attempts_per_request{bucket="1"} 23732
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11336
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12139
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 138
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 28952
telemt_me_reconnect_success_total 17659
telemt_me_reader_eof_total 19144
telemt_me_idle_close_by_peer_total 19142
telemt_me_route_drop_no_conn_total 795647
telemt_me_route_drop_channel_closed_total 90
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1130374
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2135
telemt_desync_full_logged_total 747
telemt_desync_suppressed_total 1388
telemt_desync_frames_bucket_total{bucket="1_2"} 469
telemt_desync_frames_bucket_total{bucket="3_10"} 810
telemt_desync_frames_bucket_total{bucket="gt_10"} 856
telemt_pool_swap_total 107
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 18284
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 17645
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 625
telemt_user_connections_total{user="hello"} 946003
telemt_user_connections_current{user="hello"} 531
telemt_user_octets_from_client{user="hello"} 15120900380 (14.08 GB)
telemt_user_octets_to_client{user="hello"} 414780169952 (386.29 GB)
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 66742.9 (18h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 463870
telemt_connections_bad_total 46961
telemt_handshake_timeouts_total 11949
telemt_upstream_connect_attempt_total 24184
telemt_upstream_connect_success_total 23940
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 24184
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12806
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11038
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 32056
telemt_me_reconnect_success_total 20445
telemt_me_reader_eof_total 21613
telemt_me_idle_close_by_peer_total 21613
telemt_me_seq_mismatch_total 32
telemt_me_route_drop_no_conn_total 113118
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 335028
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 36
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1469
telemt_desync_full_logged_total 478
telemt_desync_suppressed_total 991
telemt_desync_frames_bucket_total{bucket="1_2"} 244
telemt_desync_frames_bucket_total{bucket="3_10"} 663
telemt_desync_frames_bucket_total{bucket="gt_10"} 562
telemt_pool_swap_total 45
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 21028
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 20403
telemt_me_writer_restored_fallback_total 42
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 583
telemt_user_connections_total{user="hello"} 334821
telemt_user_connections_current{user="hello"} 586
telemt_user_octets_from_client{user="hello"} 23101777293 (21.52 GB)
telemt_user_octets_to_client{user="hello"} 276633513538 (257.64 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 63
```