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

# Server Metrics 2026-03-14 21:29:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 29592.7 (8h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 142881
telemt_connections_bad_total 16352
telemt_handshake_timeouts_total 1516
telemt_upstream_connect_attempt_total 6655
telemt_upstream_connect_success_total 6653
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 6655
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3146
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3424
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 224
telemt_me_reconnect_attempts_total 5190
telemt_me_reconnect_success_total 5152
telemt_me_reader_eof_total 5469
telemt_me_idle_close_by_peer_total 5469
telemt_me_route_drop_no_conn_total 51866
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 118540
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 570
telemt_desync_full_logged_total 197
telemt_desync_suppressed_total 373
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 206
telemt_desync_frames_bucket_total{bucket="gt_10"} 237
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 5236
telemt_me_writer_restored_same_endpoint_total 5134
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 118460
telemt_user_connections_current{user="hello"} 236
telemt_user_octets_from_client{user="hello"} 2512978512 (2.34 GB)
telemt_user_octets_to_client{user="hello"} 72327591820 (67.36 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 29591.0 (8h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59284
telemt_connections_bad_total 735
telemt_handshake_timeouts_total 996
telemt_upstream_connect_attempt_total 7647
telemt_upstream_connect_success_total 7599
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 7647
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3137
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4326
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 136
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 8678
telemt_me_reconnect_success_total 6098
telemt_me_reader_eof_total 6487
telemt_me_idle_close_by_peer_total 6487
telemt_me_route_drop_no_conn_total 32150
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 55326
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 6259
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 6093
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 161
telemt_user_connections_total{user="hello"} 55247
telemt_user_connections_current{user="hello"} 115
telemt_user_octets_from_client{user="hello"} 1382473588 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 24979678188 (23.26 GB)
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 29595.4 (8h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66649
telemt_connections_bad_total 395
telemt_handshake_timeouts_total 1912
telemt_upstream_connect_attempt_total 9697
telemt_upstream_connect_success_total 9597
telemt_upstream_connect_fail_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 9697
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4471
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5113
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 100
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 105643
telemt_me_reconnect_success_total 7778
telemt_me_reader_eof_total 8292
telemt_me_idle_close_by_peer_total 8292
telemt_me_route_drop_no_conn_total 24872
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 60957
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 8061
telemt_me_refill_failed_total 3169
telemt_me_writer_restored_same_endpoint_total 7732
telemt_me_writer_restored_fallback_total 46
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 283
telemt_user_connections_total{user="hello"} 61020
telemt_user_connections_current{user="hello"} 94
telemt_user_octets_from_client{user="hello"} 3915083417 (3.65 GB)
telemt_user_octets_to_client{user="hello"} 46699154834 (43.49 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 29600.2 (8h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84564
telemt_connections_bad_total 208
telemt_handshake_timeouts_total 619
telemt_upstream_connect_attempt_total 7215
telemt_upstream_connect_success_total 7171
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 7215
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3360
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3781
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 203
telemt_me_reconnect_attempts_total 5534
telemt_me_reconnect_success_total 5505
telemt_me_reader_eof_total 5802
telemt_me_idle_close_by_peer_total 5802
telemt_me_route_drop_no_conn_total 36563
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 80148
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 657
telemt_desync_full_logged_total 168
telemt_desync_suppressed_total 489
telemt_desync_frames_bucket_total{bucket="1_2"} 119
telemt_desync_frames_bucket_total{bucket="3_10"} 275
telemt_desync_frames_bucket_total{bucket="gt_10"} 263
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 5565
telemt_me_writer_restored_same_endpoint_total 5503
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 80192
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 1333641224 (1.24 GB)
telemt_user_octets_to_client{user="hello"} 28771040438 (26.80 GB)
telemt_user_msgs_from_client{user="hello"} 473
telemt_user_msgs_to_client{user="hello"} 2783
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 29593.5 (8h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63647
telemt_connections_bad_total 5783
telemt_handshake_timeouts_total 3381
telemt_upstream_connect_attempt_total 7187
telemt_upstream_connect_success_total 7105
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 7187
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3208
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3850
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 220
telemt_me_reconnect_attempts_total 12138
telemt_me_reconnect_success_total 5600
telemt_me_reader_eof_total 6062
telemt_me_idle_close_by_peer_total 6062
telemt_me_route_drop_no_conn_total 20551
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 51294
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 270
telemt_desync_full_logged_total 41
telemt_desync_suppressed_total 229
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 96
telemt_desync_frames_bucket_total{bucket="gt_10"} 136
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 5857
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 5596
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 257
telemt_user_connections_total{user="hello"} 51280
telemt_user_connections_current{user="hello"} 67
telemt_user_octets_from_client{user="hello"} 1408410752 (1.31 GB)
telemt_user_octets_to_client{user="hello"} 31893745876 (29.70 GB)
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 29593.0 (8h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 214258
telemt_connections_bad_total 7386
telemt_handshake_timeouts_total 2691
telemt_upstream_connect_attempt_total 5889
telemt_upstream_connect_success_total 5780
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 5889
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2812
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2963
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 261
telemt_me_reconnect_attempts_total 9288
telemt_me_reconnect_success_total 4279
telemt_me_reader_eof_total 4630
telemt_me_idle_close_by_peer_total 4630
telemt_me_route_drop_no_conn_total 119471
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 197912
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 115
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 84
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 4487
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 4275
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 208
telemt_user_connections_total{user="hello"} 194397
telemt_user_connections_current{user="hello"} 353
telemt_user_octets_from_client{user="hello"} 5159784996 (4.81 GB)
telemt_user_octets_to_client{user="hello"} 107052965080 (99.70 GB)
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 43
```