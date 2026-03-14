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

# Server Metrics 2026-03-14 19:37:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 22853.2 (6h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 122132
telemt_connections_bad_total 15865
telemt_handshake_timeouts_total 1163
telemt_upstream_connect_attempt_total 5231
telemt_upstream_connect_success_total 5229
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 5231
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2485
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2669
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 186
telemt_me_reconnect_attempts_total 4069
telemt_me_reconnect_success_total 4034
telemt_me_reader_eof_total 4275
telemt_me_idle_close_by_peer_total 4275
telemt_me_route_drop_no_conn_total 43015
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 99748
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 412
telemt_desync_full_logged_total 151
telemt_desync_suppressed_total 261
telemt_desync_frames_bucket_total{bucket="1_2"} 104
telemt_desync_frames_bucket_total{bucket="3_10"} 156
telemt_desync_frames_bucket_total{bucket="gt_10"} 152
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 4100
telemt_me_writer_restored_same_endpoint_total 4016
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 99676
telemt_user_connections_current{user="hello"} 362
telemt_user_octets_from_client{user="hello"} 1992784600 (1.86 GB)
telemt_user_octets_to_client{user="hello"} 50275342432 (46.82 GB)
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 22851.0 (6h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49543
telemt_connections_bad_total 668
telemt_handshake_timeouts_total 910
telemt_upstream_connect_attempt_total 5980
telemt_upstream_connect_success_total 5939
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 5980
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2410
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3414
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 110
telemt_me_reconnect_attempts_total 7320
telemt_me_reconnect_success_total 4745
telemt_me_reader_eof_total 5048
telemt_me_idle_close_by_peer_total 5048
telemt_me_route_drop_no_conn_total 26327
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 46133
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 4890
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 4740
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 145
telemt_user_connections_total{user="hello"} 46128
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 662586816 (631.89 MB)
telemt_user_octets_to_client{user="hello"} 19476795188 (18.14 GB)
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 22855.4 (6h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54633
telemt_connections_bad_total 385
telemt_handshake_timeouts_total 1859
telemt_upstream_connect_attempt_total 7858
telemt_upstream_connect_success_total 7775
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 7858
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3692
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4078
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 189
telemt_me_reconnect_attempts_total 104124
telemt_me_reconnect_success_total 6261
telemt_me_reader_eof_total 6687
telemt_me_idle_close_by_peer_total 6687
telemt_me_route_drop_no_conn_total 21135
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 49446
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 8
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
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 6528
telemt_me_refill_failed_total 3169
telemt_me_writer_restored_same_endpoint_total 6220
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 267
telemt_user_connections_total{user="hello"} 49514
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 3171594749 (2.95 GB)
telemt_user_octets_to_client{user="hello"} 35413917914 (32.98 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 22860.1 (6h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69900
telemt_connections_bad_total 181
telemt_handshake_timeouts_total 567
telemt_upstream_connect_attempt_total 5587
telemt_upstream_connect_success_total 5553
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 5587
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2530
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3000
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 4390
telemt_me_reconnect_success_total 4366
telemt_me_reader_eof_total 4587
telemt_me_idle_close_by_peer_total 4587
telemt_me_route_drop_no_conn_total 30854
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 66145
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 567
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 424
telemt_desync_frames_bucket_total{bucket="1_2"} 96
telemt_desync_frames_bucket_total{bucket="3_10"} 232
telemt_desync_frames_bucket_total{bucket="gt_10"} 239
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 4413
telemt_me_writer_restored_same_endpoint_total 4364
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 66021
telemt_user_connections_current{user="hello"} 221
telemt_user_octets_from_client{user="hello"} 928095304 (885.10 MB)
telemt_user_octets_to_client{user="hello"} 20887790816 (19.45 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 22853.3 (6h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51665
telemt_connections_bad_total 4408
telemt_handshake_timeouts_total 3212
telemt_upstream_connect_attempt_total 5306
telemt_upstream_connect_success_total 5246
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 5306
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2360
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2858
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 129
telemt_me_reconnect_attempts_total 10582
telemt_me_reconnect_success_total 4051
telemt_me_reader_eof_total 4430
telemt_me_idle_close_by_peer_total 4430
telemt_me_route_drop_no_conn_total 17526
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 41605
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 251
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 214
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 89
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 4295
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 4047
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 244
telemt_user_connections_total{user="hello"} 41593
telemt_user_connections_current{user="hello"} 83
telemt_user_octets_from_client{user="hello"} 664112324 (633.35 MB)
telemt_user_octets_to_client{user="hello"} 14579571404 (13.58 GB)
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 22853.0 (6h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 179940
telemt_connections_bad_total 7212
telemt_handshake_timeouts_total 2614
telemt_upstream_connect_attempt_total 4489
telemt_upstream_connect_success_total 4411
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 4489
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2166
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2243
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_keepalive_timeout_total 101
telemt_me_reconnect_attempts_total 8219
telemt_me_reconnect_success_total 3218
telemt_me_reader_eof_total 3498
telemt_me_idle_close_by_peer_total 3498
telemt_me_route_drop_no_conn_total 101729
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 164830
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 55
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 35
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3408
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 3214
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 190
telemt_user_connections_total{user="hello"} 161320
telemt_user_connections_current{user="hello"} 466
telemt_user_octets_from_client{user="hello"} 3487804912 (3.25 GB)
telemt_user_octets_to_client{user="hello"} 80463607208 (74.94 GB)
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 56
```