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

# Server Metrics 2026-03-13 16:47:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 119630.6 (33h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 500444
telemt_connections_bad_total 4988
telemt_handshake_timeouts_total 10183
telemt_upstream_connect_attempt_total 29716
telemt_upstream_connect_success_total 29572
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 29716
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13365
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16143
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2602
telemt_me_reconnect_attempts_total 27146
telemt_me_reconnect_success_total 23604
telemt_me_reader_eof_total 25219
telemt_me_idle_close_by_peer_total 25218
telemt_me_route_drop_no_conn_total 163200
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 438032
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1403
telemt_desync_full_logged_total 492
telemt_desync_suppressed_total 911
telemt_desync_frames_bucket_total{bucket="1_2"} 308
telemt_desync_frames_bucket_total{bucket="3_10"} 505
telemt_desync_frames_bucket_total{bucket="gt_10"} 590
telemt_pool_swap_total 109
telemt_me_writer_removed_unexpected_total 23968
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 23588
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 364
telemt_user_connections_total{user="hello"} 437603
telemt_user_connections_current{user="hello"} 305
telemt_user_octets_from_client{user="hello"} 7969297428 (7.42 GB)
telemt_user_octets_to_client{user="hello"} 203185361232 (189.23 GB)
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 119523.9 (33h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 243840
telemt_connections_bad_total 1885
telemt_handshake_timeouts_total 1767
telemt_upstream_connect_attempt_total 99470
telemt_upstream_connect_success_total 98658
telemt_upstream_connect_fail_total 812
telemt_upstream_connect_attempts_per_request{bucket="1"} 99470
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72052
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25294
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1312
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 812
telemt_me_keepalive_timeout_total 1468
telemt_me_reconnect_attempts_total 120448
telemt_me_reconnect_success_total 26033
telemt_me_reader_eof_total 29737
telemt_me_idle_close_by_peer_total 29737
telemt_me_route_drop_no_conn_total 81926
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 164328
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 29207
telemt_me_refill_failed_total 2946
telemt_me_writer_restored_same_endpoint_total 26016
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3174
telemt_user_connections_total{user="hello"} 230777
telemt_user_connections_current{user="hello"} 240
telemt_user_octets_from_client{user="hello"} 2424024748 (2.26 GB)
telemt_user_octets_to_client{user="hello"} 71612480850 (66.69 GB)
telemt_user_msgs_from_client{user="hello"} 1043903
telemt_user_msgs_to_client{user="hello"} 6154069
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 119488.3 (33h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 290983
telemt_connections_bad_total 2448
telemt_handshake_timeouts_total 14882
telemt_upstream_connect_attempt_total 31964
telemt_upstream_connect_success_total 31960
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 31964
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14838
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17091
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2473
telemt_me_reconnect_attempts_total 27176
telemt_me_reconnect_success_total 25952
telemt_me_reader_eof_total 27812
telemt_me_idle_close_by_peer_total 27812
telemt_me_route_drop_no_conn_total 104374
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 263354
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 103
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_pool_swap_total 108
telemt_me_writer_removed_unexpected_total 26242
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 25932
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 290
telemt_user_connections_total{user="hello"} 263264
telemt_user_connections_current{user="hello"} 142
telemt_user_octets_from_client{user="hello"} 10102801832 (9.41 GB)
telemt_user_octets_to_client{user="hello"} 110221783816 (102.65 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 119462.7 (33h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 395066
telemt_connections_bad_total 15069
telemt_handshake_timeouts_total 3834
telemt_upstream_connect_attempt_total 49475
telemt_upstream_connect_success_total 39273
telemt_upstream_connect_fail_total 10202
telemt_upstream_connect_attempts_per_request{bucket="1"} 49475
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22305
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16740
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 219
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10202
telemt_me_keepalive_timeout_total 4217
telemt_me_reconnect_attempts_total 109887
telemt_me_reconnect_success_total 24339
telemt_me_reader_eof_total 27717
telemt_me_idle_close_by_peer_total 27710
telemt_me_route_drop_no_conn_total 139466
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 338018
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1350
telemt_desync_full_logged_total 402
telemt_desync_suppressed_total 948
telemt_desync_frames_bucket_total{bucket="1_2"} 331
telemt_desync_frames_bucket_total{bucket="3_10"} 520
telemt_desync_frames_bucket_total{bucket="gt_10"} 499
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 27320
telemt_me_refill_failed_total 2668
telemt_me_writer_restored_same_endpoint_total 24329
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2981
telemt_user_connections_total{user="hello"} 346854
telemt_user_connections_current{user="hello"} 200
telemt_user_octets_from_client{user="hello"} 8219112732 (7.65 GB)
telemt_user_octets_to_client{user="hello"} 127012987447 (118.29 GB)
telemt_user_msgs_from_client{user="hello"} 337425
telemt_user_msgs_to_client{user="hello"} 425075
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 69634.3 (19h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 111399
telemt_connections_bad_total 14478
telemt_handshake_timeouts_total 1372
telemt_upstream_connect_attempt_total 27914
telemt_upstream_connect_success_total 27664
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 27914
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14369
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13212
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_keepalive_timeout_total 1109
telemt_me_reconnect_attempts_total 30442
telemt_me_reconnect_success_total 19264
telemt_me_reader_eof_total 20626
telemt_me_idle_close_by_peer_total 20626
telemt_me_route_drop_no_conn_total 34393
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 87081
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 390
telemt_desync_full_logged_total 76
telemt_desync_suppressed_total 314
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 214
telemt_desync_frames_bucket_total{bucket="gt_10"} 124
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 19783
telemt_me_refill_failed_total 347
telemt_me_writer_restored_same_endpoint_total 19246
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 519
telemt_user_connections_total{user="hello"} 91980
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 1043284905 (994.95 MB)
telemt_user_octets_to_client{user="hello"} 28558000315 (26.60 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 119419.7 (33h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 728541
telemt_connections_bad_total 24641
telemt_handshake_timeouts_total 24206
telemt_upstream_connect_attempt_total 24978
telemt_upstream_connect_success_total 24853
telemt_upstream_connect_fail_total 125
telemt_upstream_connect_attempts_per_request{bucket="1"} 24978
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11673
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13155
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 125
telemt_me_keepalive_timeout_total 2645
telemt_me_reconnect_attempts_total 23556
telemt_me_reconnect_success_total 18923
telemt_me_reader_eof_total 20297
telemt_me_idle_close_by_peer_total 20294
telemt_me_route_drop_no_conn_total 344340
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 682984
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 667
telemt_desync_full_logged_total 217
telemt_desync_suppressed_total 450
telemt_desync_frames_bucket_total{bucket="1_2"} 236
telemt_desync_frames_bucket_total{bucket="3_10"} 221
telemt_desync_frames_bucket_total{bucket="gt_10"} 210
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 19309
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 18916
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 386
telemt_user_connections_total{user="hello"} 655873
telemt_user_connections_current{user="hello"} 423
telemt_user_octets_from_client{user="hello"} 11364493780 (10.58 GB)
telemt_user_octets_to_client{user="hello"} 333286406264 (310.40 GB)
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 56
```