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

# Server Metrics 2026-03-18 01:47:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 111730.2 (31h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1296435
telemt_connections_bad_total 9661
telemt_handshake_timeouts_total 32541
telemt_upstream_connect_attempt_total 24908
telemt_upstream_connect_success_total 24405
telemt_upstream_connect_fail_total 503
telemt_upstream_connect_attempts_per_request{bucket="1"} 24908
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12527
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11670
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 503
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 33666
telemt_me_reconnect_success_total 16527
telemt_me_reader_eof_total 17944
telemt_me_idle_close_by_peer_total 17943
telemt_me_route_drop_no_conn_total 564973
telemt_me_route_drop_channel_closed_total 158
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1193234
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7628
telemt_desync_full_logged_total 2249
telemt_desync_suppressed_total 5379
telemt_desync_frames_bucket_total{bucket="1_2"} 2045
telemt_desync_frames_bucket_total{bucket="3_10"} 2892
telemt_desync_frames_bucket_total{bucket="gt_10"} 2691
telemt_pool_swap_total 93
telemt_me_writer_removed_unexpected_total 17308
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 16505
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 781
telemt_user_connections_total{user="hello"} 1187446
telemt_user_connections_current{user="hello"} 483
telemt_user_octets_from_client{user="hello"} 22981710867 (21.40 GB)
telemt_user_octets_to_client{user="hello"} 422251742379 (393.25 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 223
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 111981.1 (31h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1372551
telemt_connections_bad_total 64199
telemt_handshake_timeouts_total 46762
telemt_upstream_connect_attempt_total 467621
telemt_upstream_connect_success_total 466054
telemt_upstream_connect_fail_total 1567
telemt_upstream_connect_attempts_per_request{bucket="1"} 467621
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 389643
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33055
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43354
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1567
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 122982
telemt_me_reconnect_success_total 17544
telemt_me_reader_eof_total 19700
telemt_me_idle_close_by_peer_total 19687
telemt_me_route_drop_no_conn_total 353885
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 749468
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3477
telemt_desync_full_logged_total 1173
telemt_desync_suppressed_total 2304
telemt_desync_frames_bucket_total{bucket="1_2"} 680
telemt_desync_frames_bucket_total{bucket="3_10"} 1442
telemt_desync_frames_bucket_total{bucket="gt_10"} 1355
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 19107
telemt_me_refill_failed_total 3289
telemt_me_writer_restored_same_endpoint_total 17526
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1563
telemt_user_connections_total{user="hello"} 1191818
telemt_user_connections_current{user="hello"} 588
telemt_user_octets_from_client{user="hello"} 16162659637 (15.05 GB)
telemt_user_octets_to_client{user="hello"} 415971810838 (387.40 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 243
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 111756.9 (31h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 820422
telemt_connections_bad_total 55645
telemt_handshake_timeouts_total 24357
telemt_upstream_connect_attempt_total 26186
telemt_upstream_connect_success_total 26034
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 26186
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11949
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13987
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 41091
telemt_me_reconnect_success_total 20401
telemt_me_reader_eof_total 22209
telemt_me_idle_close_by_peer_total 22202
telemt_me_route_drop_no_conn_total 328471
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 694849
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2196
telemt_desync_full_logged_total 715
telemt_desync_suppressed_total 1481
telemt_desync_frames_bucket_total{bucket="1_2"} 624
telemt_desync_frames_bucket_total{bucket="3_10"} 850
telemt_desync_frames_bucket_total{bucket="gt_10"} 722
telemt_pool_swap_total 90
telemt_me_writer_removed_unexpected_total 21322
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 20389
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 921
telemt_user_connections_total{user="hello"} 692969
telemt_user_connections_current{user="hello"} 405
telemt_user_octets_from_client{user="hello"} 41478298804 (38.63 GB)
telemt_user_octets_to_client{user="hello"} 306683602312 (285.62 GB)
telemt_user_unique_ips_current{user="hello"} 169
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 111816.5 (31h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1304839
telemt_connections_bad_total 56870
telemt_handshake_timeouts_total 22052
telemt_upstream_connect_attempt_total 88996
telemt_upstream_connect_success_total 86587
telemt_upstream_connect_fail_total 2409
telemt_upstream_connect_attempts_per_request{bucket="1"} 88996
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72513
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13677
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 367
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2409
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 36624
telemt_me_reconnect_success_total 16230
telemt_me_reader_eof_total 17891
telemt_me_idle_close_by_peer_total 17889
telemt_me_route_drop_no_conn_total 536351
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1060275
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3957
telemt_desync_full_logged_total 1310
telemt_desync_suppressed_total 2647
telemt_desync_frames_bucket_total{bucket="1_2"} 968
telemt_desync_frames_bucket_total{bucket="3_10"} 1660
telemt_desync_frames_bucket_total{bucket="gt_10"} 1329
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 17172
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 16219
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 942
telemt_user_connections_total{user="hello"} 1123683
telemt_user_connections_current{user="hello"} 557
telemt_user_octets_from_client{user="hello"} 17627893898 (16.42 GB)
telemt_user_octets_to_client{user="hello"} 529816265094 (493.43 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 111788.4 (31h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 861699
telemt_connections_bad_total 100011
telemt_handshake_timeouts_total 6851
telemt_upstream_connect_attempt_total 45748
telemt_upstream_connect_success_total 45120
telemt_upstream_connect_fail_total 628
telemt_upstream_connect_attempts_per_request{bucket="1"} 45748
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28243
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16465
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 412
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 628
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 58006
telemt_me_reconnect_success_total 23044
telemt_me_reader_eof_total 24994
telemt_me_idle_close_by_peer_total 24991
telemt_me_route_drop_no_conn_total 273949
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 695517
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3209
telemt_desync_full_logged_total 957
telemt_desync_suppressed_total 2252
telemt_desync_frames_bucket_total{bucket="1_2"} 1008
telemt_desync_frames_bucket_total{bucket="3_10"} 1283
telemt_desync_frames_bucket_total{bucket="gt_10"} 918
telemt_pool_swap_total 56
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 24505
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 23036
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1461
telemt_user_connections_total{user="hello"} 712118
telemt_user_connections_current{user="hello"} 496
telemt_user_octets_from_client{user="hello"} 13765306528 (12.82 GB)
telemt_user_octets_to_client{user="hello"} 353169040412 (328.91 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 207
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 111949.4 (31h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1108370
telemt_connections_bad_total 115061
telemt_handshake_timeouts_total 9700
telemt_upstream_connect_attempt_total 22278
telemt_upstream_connect_success_total 22150
telemt_upstream_connect_fail_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 22278
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10614
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11417
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 128
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 27854
telemt_me_reconnect_success_total 16566
telemt_me_reader_eof_total 17970
telemt_me_idle_close_by_peer_total 17968
telemt_me_route_drop_no_conn_total 756203
telemt_me_route_drop_channel_closed_total 88
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1078826
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2106
telemt_desync_full_logged_total 737
telemt_desync_suppressed_total 1369
telemt_desync_frames_bucket_total{bucket="1_2"} 461
telemt_desync_frames_bucket_total{bucket="3_10"} 802
telemt_desync_frames_bucket_total{bucket="gt_10"} 843
telemt_pool_swap_total 99
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 17182
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 16552
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 616
telemt_user_connections_total{user="hello"} 913094
telemt_user_connections_current{user="hello"} 377
telemt_user_octets_from_client{user="hello"} 14833373132 (13.81 GB)
telemt_user_octets_to_client{user="hello"} 394614917372 (367.51 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 59716.7 (16h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 415442
telemt_connections_bad_total 44714
telemt_handshake_timeouts_total 10999
telemt_upstream_connect_attempt_total 22207
telemt_upstream_connect_success_total 21998
telemt_upstream_connect_fail_total 209
telemt_upstream_connect_attempts_per_request{bucket="1"} 22207
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11796
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10106
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 209
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 30460
telemt_me_reconnect_success_total 18854
telemt_me_reader_eof_total 19942
telemt_me_idle_close_by_peer_total 19942
telemt_me_seq_mismatch_total 26
telemt_me_route_drop_no_conn_total 102932
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 301242
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 30
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1280
telemt_desync_full_logged_total 397
telemt_desync_suppressed_total 883
telemt_desync_frames_bucket_total{bucket="1_2"} 223
telemt_desync_frames_bucket_total{bucket="3_10"} 568
telemt_desync_frames_bucket_total{bucket="gt_10"} 489
telemt_pool_swap_total 39
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19426
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 18818
telemt_me_writer_restored_fallback_total 36
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 572
telemt_user_connections_total{user="hello"} 301178
telemt_user_connections_current{user="hello"} 317
telemt_user_octets_from_client{user="hello"} 22497971265 (20.95 GB)
telemt_user_octets_to_client{user="hello"} 254087575838 (236.64 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 29
```