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

# Server Metrics 2026-03-13 04:08:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 74118.8 (20h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 285075
telemt_connections_bad_total 3007
telemt_handshake_timeouts_total 5762
telemt_upstream_connect_attempt_total 18751
telemt_upstream_connect_success_total 18666
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 18751
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8334
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10286
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1534
telemt_me_reconnect_attempts_total 18418
telemt_me_reconnect_success_total 14929
telemt_me_reader_eof_total 15960
telemt_me_idle_close_by_peer_total 15959
telemt_me_route_drop_no_conn_total 88680
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 238590
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 793
telemt_desync_full_logged_total 295
telemt_desync_suppressed_total 498
telemt_desync_frames_bucket_total{bucket="1_2"} 150
telemt_desync_frames_bucket_total{bucket="3_10"} 287
telemt_desync_frames_bucket_total{bucket="gt_10"} 356
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 15200
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 14913
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 271
telemt_user_connections_total{user="hello"} 238529
telemt_user_connections_current{user="hello"} 224
telemt_user_octets_from_client{user="hello"} 4156541572 (3.87 GB)
telemt_user_octets_to_client{user="hello"} 117385176196 (109.32 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 74011.8 (20h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 131277
telemt_connections_bad_total 748
telemt_handshake_timeouts_total 983
telemt_upstream_connect_attempt_total 40063
telemt_upstream_connect_success_total 39567
telemt_upstream_connect_fail_total 496
telemt_upstream_connect_attempts_per_request{bucket="1"} 40063
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23924
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15140
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 503
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 496
telemt_me_keepalive_timeout_total 536
telemt_me_reconnect_attempts_total 65906
telemt_me_reconnect_success_total 19346
telemt_me_reader_eof_total 21372
telemt_me_idle_close_by_peer_total 21372
telemt_me_route_drop_no_conn_total 47926
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 108233
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 20947
telemt_me_refill_failed_total 1453
telemt_me_writer_restored_same_endpoint_total 19331
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1601
telemt_user_connections_total{user="hello"} 124733
telemt_user_connections_current{user="hello"} 89
telemt_user_octets_from_client{user="hello"} 1296903720 (1.21 GB)
telemt_user_octets_to_client{user="hello"} 37499114939 (34.92 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 73975.1 (20h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 158153
telemt_connections_bad_total 1832
telemt_handshake_timeouts_total 2579
telemt_upstream_connect_attempt_total 20514
telemt_upstream_connect_success_total 20512
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 20514
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9468
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11021
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 404
telemt_me_reconnect_attempts_total 17913
telemt_me_reconnect_success_total 16749
telemt_me_reader_eof_total 17937
telemt_me_idle_close_by_peer_total 17937
telemt_me_route_drop_no_conn_total 61197
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 147915
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
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 16934
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 16729
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 185
telemt_user_connections_total{user="hello"} 147840
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 2780441544 (2.59 GB)
telemt_user_octets_to_client{user="hello"} 69541332652 (64.77 GB)
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 73950.9 (20h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 227277
telemt_connections_bad_total 13471
telemt_handshake_timeouts_total 1448
telemt_upstream_connect_attempt_total 32968
telemt_upstream_connect_success_total 23113
telemt_upstream_connect_fail_total 9855
telemt_upstream_connect_attempts_per_request{bucket="1"} 32968
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11628
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11315
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 162
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9855
telemt_me_keepalive_timeout_total 3307
telemt_me_reconnect_attempts_total 60444
telemt_me_reconnect_success_total 16532
telemt_me_reader_eof_total 18426
telemt_me_idle_close_by_peer_total 18419
telemt_me_route_drop_no_conn_total 83005
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 189885
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 505
telemt_desync_full_logged_total 145
telemt_desync_suppressed_total 360
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 188
telemt_desync_frames_bucket_total{bucket="gt_10"} 190
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 18127
telemt_me_refill_failed_total 1368
telemt_me_writer_restored_same_endpoint_total 16522
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1595
telemt_user_connections_total{user="hello"} 192633
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 3198200786 (2.98 GB)
telemt_user_octets_to_client{user="hello"} 78097511341 (72.73 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 24122.6 (6h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24052
telemt_connections_bad_total 4522
telemt_handshake_timeouts_total 92
telemt_upstream_connect_attempt_total 7494
telemt_upstream_connect_success_total 7425
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 7494
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3240
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4155
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 171
telemt_me_reconnect_attempts_total 6239
telemt_me_reconnect_success_total 6217
telemt_me_reader_eof_total 6666
telemt_me_idle_close_by_peer_total 6666
telemt_me_route_drop_no_conn_total 6763
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18751
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 6271
telemt_me_writer_restored_same_endpoint_total 6199
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 18751
telemt_user_connections_current{user="hello"} 55
telemt_user_octets_from_client{user="hello"} 136664540 (130.33 MB)
telemt_user_octets_to_client{user="hello"} 8857651480 (8.25 GB)
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 73907.4 (20h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 382976
telemt_connections_bad_total 7503
telemt_handshake_timeouts_total 2906
telemt_upstream_connect_attempt_total 15732
telemt_upstream_connect_success_total 15646
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 15732
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7284
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8337
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_timeout_total 1426
telemt_me_reconnect_attempts_total 15573
telemt_me_reconnect_success_total 11946
telemt_me_reader_eof_total 12824
telemt_me_idle_close_by_peer_total 12821
telemt_me_route_drop_no_conn_total 171185
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 373579
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 314
telemt_desync_full_logged_total 123
telemt_desync_suppressed_total 191
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 116
telemt_desync_frames_bucket_total{bucket="gt_10"} 123
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 12213
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 11939
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 267
telemt_user_connections_total{user="hello"} 361825
telemt_user_connections_current{user="hello"} 252
telemt_user_octets_from_client{user="hello"} 6046681716 (5.63 GB)
telemt_user_octets_to_client{user="hello"} 217057681156 (202.15 GB)
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 30
```