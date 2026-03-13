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

# Server Metrics 2026-03-13 07:18:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 85484.7 (23h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 327003
telemt_connections_bad_total 3143
telemt_handshake_timeouts_total 7008
telemt_upstream_connect_attempt_total 21456
telemt_upstream_connect_success_total 21358
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 21456
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9616
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11694
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1650
telemt_me_reconnect_attempts_total 20589
telemt_me_reconnect_success_total 17086
telemt_me_reader_eof_total 18269
telemt_me_idle_close_by_peer_total 18268
telemt_me_route_drop_no_conn_total 102785
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 277762
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 944
telemt_desync_full_logged_total 349
telemt_desync_suppressed_total 595
telemt_desync_frames_bucket_total{bucket="1_2"} 187
telemt_desync_frames_bucket_total{bucket="3_10"} 345
telemt_desync_frames_bucket_total{bucket="gt_10"} 412
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 17379
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 17070
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 293
telemt_user_connections_total{user="hello"} 277460
telemt_user_connections_current{user="hello"} 319
telemt_user_octets_from_client{user="hello"} 4658918668 (4.34 GB)
telemt_user_octets_to_client{user="hello"} 130790684660 (121.81 GB)
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 85377.6 (23h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 149232
telemt_connections_bad_total 1422
telemt_handshake_timeouts_total 1146
telemt_upstream_connect_attempt_total 44232
telemt_upstream_connect_success_total 43650
telemt_upstream_connect_fail_total 582
telemt_upstream_connect_attempts_per_request{bucket="1"} 44232
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25592
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17547
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 511
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 582
telemt_me_keepalive_timeout_total 659
telemt_me_reconnect_attempts_total 73116
telemt_me_reconnect_success_total 22898
telemt_me_reader_eof_total 25149
telemt_me_idle_close_by_peer_total 25149
telemt_me_route_drop_no_conn_total 56360
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 124768
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 17
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
telemt_me_writer_removed_unexpected_total 24648
telemt_me_refill_failed_total 1567
telemt_me_writer_restored_same_endpoint_total 22883
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1750
telemt_user_connections_total{user="hello"} 141260
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 1455529612 (1.36 GB)
telemt_user_octets_to_client{user="hello"} 45563049695 (42.43 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 85341.3 (23h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 180991
telemt_connections_bad_total 1971
telemt_handshake_timeouts_total 2926
telemt_upstream_connect_attempt_total 23229
telemt_upstream_connect_success_total 23227
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 23229
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10696
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12508
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 558
telemt_me_reconnect_attempts_total 20109
telemt_me_reconnect_success_total 18934
telemt_me_reader_eof_total 20297
telemt_me_idle_close_by_peer_total 20297
telemt_me_route_drop_no_conn_total 69944
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 169367
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
telemt_pool_swap_total 78
telemt_me_writer_removed_unexpected_total 19139
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 18914
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 205
telemt_user_connections_total{user="hello"} 169295
telemt_user_connections_current{user="hello"} 129
telemt_user_octets_from_client{user="hello"} 3012327824 (2.81 GB)
telemt_user_octets_to_client{user="hello"} 74002310208 (68.92 GB)
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 85316.9 (23h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 259877
telemt_connections_bad_total 13614
telemt_handshake_timeouts_total 1970
telemt_upstream_connect_attempt_total 35904
telemt_upstream_connect_success_total 25959
telemt_upstream_connect_fail_total 9945
telemt_upstream_connect_attempts_per_request{bucket="1"} 35904
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13004
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12769
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 177
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9945
telemt_me_keepalive_timeout_total 3359
telemt_me_reconnect_attempts_total 70387
telemt_me_reconnect_success_total 18847
telemt_me_reader_eof_total 21056
telemt_me_idle_close_by_peer_total 21049
telemt_me_route_drop_no_conn_total 93851
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 219750
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 718
telemt_desync_full_logged_total 205
telemt_desync_suppressed_total 513
telemt_desync_frames_bucket_total{bucket="1_2"} 176
telemt_desync_frames_bucket_total{bucket="3_10"} 272
telemt_desync_frames_bucket_total{bucket="gt_10"} 270
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 20703
telemt_me_refill_failed_total 1606
telemt_me_writer_restored_same_endpoint_total 18837
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1856
telemt_user_connections_total{user="hello"} 222483
telemt_user_connections_current{user="hello"} 186
telemt_user_octets_from_client{user="hello"} 5187105714 (4.83 GB)
telemt_user_octets_to_client{user="hello"} 85524308029 (79.65 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 35488.5 (9h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42878
telemt_connections_bad_total 7314
telemt_handshake_timeouts_total 385
telemt_upstream_connect_attempt_total 12073
telemt_upstream_connect_success_total 11950
telemt_upstream_connect_fail_total 123
telemt_upstream_connect_attempts_per_request{bucket="1"} 12073
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5192
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6717
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 123
telemt_me_keepalive_timeout_total 288
telemt_me_reconnect_attempts_total 11130
telemt_me_reconnect_success_total 10162
telemt_me_reader_eof_total 10849
telemt_me_idle_close_by_peer_total 10849
telemt_me_route_drop_no_conn_total 12215
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34088
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 35
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 10285
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 10144
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 34087
telemt_user_connections_current{user="hello"} 64
telemt_user_octets_from_client{user="hello"} 249106636 (237.57 MB)
telemt_user_octets_to_client{user="hello"} 10759554280 (10.02 GB)
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 85273.5 (23h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 440875
telemt_connections_bad_total 8912
telemt_handshake_timeouts_total 3326
telemt_upstream_connect_attempt_total 18132
telemt_upstream_connect_success_total 18034
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 18132
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8414
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9595
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_keepalive_timeout_total 1501
telemt_me_reconnect_attempts_total 17442
telemt_me_reconnect_success_total 13804
telemt_me_reader_eof_total 14825
telemt_me_idle_close_by_peer_total 14822
telemt_me_route_drop_no_conn_total 194462
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 425324
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 363
telemt_desync_full_logged_total 140
telemt_desync_suppressed_total 223
telemt_desync_frames_bucket_total{bucket="1_2"} 87
telemt_desync_frames_bucket_total{bucket="3_10"} 130
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 14092
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 13797
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 288
telemt_user_connections_total{user="hello"} 413512
telemt_user_connections_current{user="hello"} 450
telemt_user_octets_from_client{user="hello"} 7762742360 (7.23 GB)
telemt_user_octets_to_client{user="hello"} 240393790520 (223.88 GB)
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 59
```