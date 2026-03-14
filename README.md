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

# Server Metrics 2026-03-14 20:02:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 24386.1 (6h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128149
telemt_connections_bad_total 15986
telemt_handshake_timeouts_total 1252
telemt_upstream_connect_attempt_total 5523
telemt_upstream_connect_success_total 5521
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 5523
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2627
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2818
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 4283
telemt_me_reconnect_success_total 4248
telemt_me_reader_eof_total 4501
telemt_me_idle_close_by_peer_total 4501
telemt_me_route_drop_no_conn_total 45760
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 105227
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 451
telemt_desync_full_logged_total 162
telemt_desync_suppressed_total 289
telemt_desync_frames_bucket_total{bucket="1_2"} 109
telemt_desync_frames_bucket_total{bucket="3_10"} 164
telemt_desync_frames_bucket_total{bucket="gt_10"} 178
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 4318
telemt_me_writer_restored_same_endpoint_total 4230
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 105148
telemt_user_connections_current{user="hello"} 296
telemt_user_octets_from_client{user="hello"} 2206561084 (2.06 GB)
telemt_user_octets_to_client{user="hello"} 55524981716 (51.71 GB)
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 24384.0 (6h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52135
telemt_connections_bad_total 683
telemt_handshake_timeouts_total 953
telemt_upstream_connect_attempt_total 6315
telemt_upstream_connect_success_total 6272
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 6314
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2565
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3588
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 7579
telemt_me_reconnect_success_total 5002
telemt_me_reader_eof_total 5319
telemt_me_idle_close_by_peer_total 5319
telemt_me_route_drop_no_conn_total 27477
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 48531
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 5153
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 4997
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 151
telemt_user_connections_total{user="hello"} 48520
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 1292220620 (1.20 GB)
telemt_user_octets_to_client{user="hello"} 20321690348 (18.93 GB)
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 24388.6 (6h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58218
telemt_connections_bad_total 386
telemt_handshake_timeouts_total 1866
telemt_upstream_connect_attempt_total 8237
telemt_upstream_connect_success_total 8151
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 8237
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3844
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4299
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_timeout_total 224
telemt_me_reconnect_attempts_total 104431
telemt_me_reconnect_success_total 6568
telemt_me_reader_eof_total 7006
telemt_me_idle_close_by_peer_total 7006
telemt_me_route_drop_no_conn_total 22269
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 52880
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 9
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
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 6838
telemt_me_refill_failed_total 3169
telemt_me_writer_restored_same_endpoint_total 6526
telemt_me_writer_restored_fallback_total 42
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 270
telemt_user_connections_total{user="hello"} 52945
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 3353228233 (3.12 GB)
telemt_user_octets_to_client{user="hello"} 39713830102 (36.99 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 24393.2 (6h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74377
telemt_connections_bad_total 204
telemt_handshake_timeouts_total 569
telemt_upstream_connect_attempt_total 6055
telemt_upstream_connect_success_total 6017
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 6055
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2825
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3166
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 178
telemt_me_reconnect_attempts_total 4601
telemt_me_reconnect_success_total 4576
telemt_me_reader_eof_total 4806
telemt_me_idle_close_by_peer_total 4806
telemt_me_route_drop_no_conn_total 32250
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 70334
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 586
telemt_desync_full_logged_total 146
telemt_desync_suppressed_total 440
telemt_desync_frames_bucket_total{bucket="1_2"} 97
telemt_desync_frames_bucket_total{bucket="3_10"} 245
telemt_desync_frames_bucket_total{bucket="gt_10"} 244
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 4628
telemt_me_writer_restored_same_endpoint_total 4574
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 70382
telemt_user_connections_current{user="hello"} 180
telemt_user_octets_from_client{user="hello"} 1040339992 (992.15 MB)
telemt_user_octets_to_client{user="hello"} 22856814870 (21.29 GB)
telemt_user_msgs_from_client{user="hello"} 473
telemt_user_msgs_to_client{user="hello"} 2783
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 24386.4 (6h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54407
telemt_connections_bad_total 4723
telemt_handshake_timeouts_total 3237
telemt_upstream_connect_attempt_total 5688
telemt_upstream_connect_success_total 5623
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 5688
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2520
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3073
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 137
telemt_me_reconnect_attempts_total 10885
telemt_me_reconnect_success_total 4352
telemt_me_reader_eof_total 4741
telemt_me_idle_close_by_peer_total 4741
telemt_me_route_drop_no_conn_total 18282
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 43887
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 252
telemt_desync_full_logged_total 38
telemt_desync_suppressed_total 214
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 89
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 4598
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 4348
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 246
telemt_user_connections_total{user="hello"} 43874
telemt_user_connections_current{user="hello"} 94
telemt_user_octets_from_client{user="hello"} 1343712136 (1.25 GB)
telemt_user_octets_to_client{user="hello"} 24045755080 (22.39 GB)
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 24386.0 (6h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 188896
telemt_connections_bad_total 7276
telemt_handshake_timeouts_total 2623
telemt_upstream_connect_attempt_total 4756
telemt_upstream_connect_success_total 4671
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 4755
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2289
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2378
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 248
telemt_me_reconnect_attempts_total 8408
telemt_me_reconnect_success_total 3403
telemt_me_reader_eof_total 3695
telemt_me_idle_close_by_peer_total 3695
telemt_me_route_drop_no_conn_total 106452
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 173447
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
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 3599
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 3399
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 196
telemt_user_connections_total{user="hello"} 169936
telemt_user_connections_current{user="hello"} 417
telemt_user_octets_from_client{user="hello"} 3660940020 (3.41 GB)
telemt_user_octets_to_client{user="hello"} 83916158280 (78.15 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 58
```