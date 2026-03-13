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

# Server Metrics 2026-03-13 07:28:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 86098.9 (23h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 330320
telemt_connections_bad_total 3167
telemt_handshake_timeouts_total 7368
telemt_upstream_connect_attempt_total 21624
telemt_upstream_connect_success_total 21525
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 21624
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9691
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11786
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1651
telemt_me_reconnect_attempts_total 20713
telemt_me_reconnect_success_total 17209
telemt_me_reader_eof_total 18404
telemt_me_idle_close_by_peer_total 18403
telemt_me_route_drop_no_conn_total 103498
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 280546
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
telemt_pool_swap_total 78
telemt_me_writer_removed_unexpected_total 17502
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 17193
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 293
telemt_user_connections_total{user="hello"} 280244
telemt_user_connections_current{user="hello"} 298
telemt_user_octets_from_client{user="hello"} 4684698572 (4.36 GB)
telemt_user_octets_to_client{user="hello"} 131315218668 (122.30 GB)
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 85991.9 (23h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 150405
telemt_connections_bad_total 1425
telemt_handshake_timeouts_total 1150
telemt_upstream_connect_attempt_total 44451
telemt_upstream_connect_success_total 43857
telemt_upstream_connect_fail_total 594
telemt_upstream_connect_attempts_per_request{bucket="1"} 44451
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25683
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17663
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 511
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 594
telemt_me_keepalive_timeout_total 666
telemt_me_reconnect_attempts_total 74624
telemt_me_reconnect_success_total 23062
telemt_me_reader_eof_total 25360
telemt_me_idle_close_by_peer_total 25360
telemt_me_route_drop_no_conn_total 56686
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 125864
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
telemt_me_writer_removed_unexpected_total 24859
telemt_me_refill_failed_total 1609
telemt_me_writer_restored_same_endpoint_total 23047
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1797
telemt_user_connections_total{user="hello"} 142356
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 1473125388 (1.37 GB)
telemt_user_octets_to_client{user="hello"} 45852665211 (42.70 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 85955.5 (23h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 182485
telemt_connections_bad_total 1971
telemt_handshake_timeouts_total 2940
telemt_upstream_connect_attempt_total 23395
telemt_upstream_connect_success_total 23393
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 23395
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10770
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12600
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 561
telemt_me_reconnect_attempts_total 20232
telemt_me_reconnect_success_total 19057
telemt_me_reader_eof_total 20434
telemt_me_idle_close_by_peer_total 20434
telemt_me_route_drop_no_conn_total 70428
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 170785
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
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 19263
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 19037
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 206
telemt_user_connections_total{user="hello"} 170714
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 3019283340 (2.81 GB)
telemt_user_octets_to_client{user="hello"} 74260459052 (69.16 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 85931.2 (23h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 262254
telemt_connections_bad_total 13616
telemt_handshake_timeouts_total 2000
telemt_upstream_connect_attempt_total 36048
telemt_upstream_connect_success_total 26102
telemt_upstream_connect_fail_total 9946
telemt_upstream_connect_attempts_per_request{bucket="1"} 36048
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13077
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12839
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 177
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9946
telemt_me_keepalive_timeout_total 3361
telemt_me_reconnect_attempts_total 70487
telemt_me_reconnect_success_total 18947
telemt_me_reader_eof_total 21165
telemt_me_idle_close_by_peer_total 21158
telemt_me_route_drop_no_conn_total 94727
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 221827
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 745
telemt_desync_full_logged_total 213
telemt_desync_suppressed_total 532
telemt_desync_frames_bucket_total{bucket="1_2"} 179
telemt_desync_frames_bucket_total{bucket="3_10"} 284
telemt_desync_frames_bucket_total{bucket="gt_10"} 282
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 20803
telemt_me_refill_failed_total 1606
telemt_me_writer_restored_same_endpoint_total 18937
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1856
telemt_user_connections_total{user="hello"} 224559
telemt_user_connections_current{user="hello"} 213
telemt_user_octets_from_client{user="hello"} 5202773134 (4.85 GB)
telemt_user_octets_to_client{user="hello"} 85995562217 (80.09 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 36102.8 (10h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43954
telemt_connections_bad_total 7424
telemt_handshake_timeouts_total 396
telemt_upstream_connect_attempt_total 12215
telemt_upstream_connect_success_total 12088
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 12215
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5260
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6786
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_keepalive_timeout_total 295
telemt_me_reconnect_attempts_total 11230
telemt_me_reconnect_success_total 10262
telemt_me_reader_eof_total 10949
telemt_me_idle_close_by_peer_total 10949
telemt_me_route_drop_no_conn_total 12561
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 35003
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
telemt_me_writer_removed_unexpected_total 10385
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 10244
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 35002
telemt_user_connections_current{user="hello"} 75
telemt_user_octets_from_client{user="hello"} 252960740 (241.24 MB)
telemt_user_octets_to_client{user="hello"} 10930058404 (10.18 GB)
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 85887.6 (23h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 445796
telemt_connections_bad_total 9601
telemt_handshake_timeouts_total 3393
telemt_upstream_connect_attempt_total 18269
telemt_upstream_connect_success_total 18171
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 18269
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8489
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9657
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_keepalive_timeout_total 1503
telemt_me_reconnect_attempts_total 17535
telemt_me_reconnect_success_total 13895
telemt_me_reader_eof_total 14926
telemt_me_idle_close_by_peer_total 14923
telemt_me_route_drop_no_conn_total 200620
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 430836
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
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 14185
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 13888
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 290
telemt_user_connections_total{user="hello"} 417449
telemt_user_connections_current{user="hello"} 421
telemt_user_octets_from_client{user="hello"} 7794748944 (7.26 GB)
telemt_user_octets_to_client{user="hello"} 242347330948 (225.70 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 64
```