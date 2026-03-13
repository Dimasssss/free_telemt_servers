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

# Server Metrics 2026-03-13 07:53:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 87635.5 (24h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 337760
telemt_connections_bad_total 3169
telemt_handshake_timeouts_total 7494
telemt_upstream_connect_attempt_total 22004
telemt_upstream_connect_success_total 21903
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 22004
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9847
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12008
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1658
telemt_me_reconnect_attempts_total 21003
telemt_me_reconnect_success_total 17498
telemt_me_reader_eof_total 18718
telemt_me_idle_close_by_peer_total 18717
telemt_me_route_drop_no_conn_total 105629
telemt_me_route_drop_channel_closed_total 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 287538
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 962
telemt_desync_full_logged_total 356
telemt_desync_suppressed_total 606
telemt_desync_frames_bucket_total{bucket="1_2"} 193
telemt_desync_frames_bucket_total{bucket="3_10"} 351
telemt_desync_frames_bucket_total{bucket="gt_10"} 418
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 17793
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 17482
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 295
telemt_user_connections_total{user="hello"} 287231
telemt_user_connections_current{user="hello"} 253
telemt_user_octets_from_client{user="hello"} 4759402212 (4.43 GB)
telemt_user_octets_to_client{user="hello"} 133145149936 (124.00 GB)
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 87528.2 (24h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 153811
telemt_connections_bad_total 1479
telemt_handshake_timeouts_total 1180
telemt_upstream_connect_attempt_total 44860
telemt_upstream_connect_success_total 44252
telemt_upstream_connect_fail_total 608
telemt_upstream_connect_attempts_per_request{bucket="1"} 44860
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25850
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17891
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 511
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 608
telemt_me_keepalive_timeout_total 674
telemt_me_reconnect_attempts_total 77363
telemt_me_reconnect_success_total 23368
telemt_me_reader_eof_total 25747
telemt_me_idle_close_by_peer_total 25747
telemt_me_route_drop_no_conn_total 57852
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 128864
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 18
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
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 25246
telemt_me_refill_failed_total 1685
telemt_me_writer_restored_same_endpoint_total 23353
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1878
telemt_user_connections_total{user="hello"} 145356
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 1509762792 (1.41 GB)
telemt_user_octets_to_client{user="hello"} 46372090247 (43.19 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 87492.1 (24h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 185832
telemt_connections_bad_total 1975
telemt_handshake_timeouts_total 3086
telemt_upstream_connect_attempt_total 23778
telemt_upstream_connect_success_total 23776
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 23778
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10944
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12809
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 568
telemt_me_reconnect_attempts_total 20529
telemt_me_reconnect_success_total 19350
telemt_me_reader_eof_total 20758
telemt_me_idle_close_by_peer_total 20758
telemt_me_route_drop_no_conn_total 71854
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 173882
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 62
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 19562
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 19330
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 212
telemt_user_connections_total{user="hello"} 173812
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 5263790584 (4.90 GB)
telemt_user_octets_to_client{user="hello"} 74589769896 (69.47 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 87467.6 (24h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 269351
telemt_connections_bad_total 13617
telemt_handshake_timeouts_total 2020
telemt_upstream_connect_attempt_total 36501
telemt_upstream_connect_success_total 26548
telemt_upstream_connect_fail_total 9953
telemt_upstream_connect_attempts_per_request{bucket="1"} 36501
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13283
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13079
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 177
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9953
telemt_me_keepalive_timeout_total 3371
telemt_me_reconnect_attempts_total 70846
telemt_me_reconnect_success_total 19302
telemt_me_reader_eof_total 21531
telemt_me_idle_close_by_peer_total 21524
telemt_me_route_drop_no_conn_total 96830
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 228338
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 830
telemt_desync_full_logged_total 243
telemt_desync_suppressed_total 587
telemt_desync_frames_bucket_total{bucket="1_2"} 212
telemt_desync_frames_bucket_total{bucket="3_10"} 305
telemt_desync_frames_bucket_total{bucket="gt_10"} 313
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 21160
telemt_me_refill_failed_total 1606
telemt_me_writer_restored_same_endpoint_total 19292
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1858
telemt_user_connections_total{user="hello"} 231066
telemt_user_connections_current{user="hello"} 222
telemt_user_octets_from_client{user="hello"} 5230438238 (4.87 GB)
telemt_user_octets_to_client{user="hello"} 88131890613 (82.08 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 37639.1 (10h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46339
telemt_connections_bad_total 7700
telemt_handshake_timeouts_total 407
telemt_upstream_connect_attempt_total 12769
telemt_upstream_connect_success_total 12639
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 12769
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5506
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7090
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_timeout_total 304
telemt_me_reconnect_attempts_total 11732
telemt_me_reconnect_success_total 10763
telemt_me_reader_eof_total 11477
telemt_me_idle_close_by_peer_total 11477
telemt_me_route_drop_no_conn_total 13452
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36953
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 71
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 62
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 10887
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 10745
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 36952
telemt_user_connections_current{user="hello"} 52
telemt_user_octets_from_client{user="hello"} 267706292 (255.30 MB)
telemt_user_octets_to_client{user="hello"} 11093584876 (10.33 GB)
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 87424.0 (24h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 459865
telemt_connections_bad_total 12935
telemt_handshake_timeouts_total 3751
telemt_upstream_connect_attempt_total 18532
telemt_upstream_connect_success_total 18431
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 18532
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8625
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9781
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_keepalive_timeout_total 1522
telemt_me_reconnect_attempts_total 17709
telemt_me_reconnect_success_total 14068
telemt_me_reader_eof_total 15113
telemt_me_idle_close_by_peer_total 15110
telemt_me_route_drop_no_conn_total 220113
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 445926
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 372
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 229
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 134
telemt_desync_frames_bucket_total{bucket="gt_10"} 149
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 14361
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 14061
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 293
telemt_user_connections_total{user="hello"} 427153
telemt_user_connections_current{user="hello"} 437
telemt_user_octets_from_client{user="hello"} 7922214496 (7.38 GB)
telemt_user_octets_to_client{user="hello"} 246692111408 (229.75 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 58
```