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

# Server Metrics 2026-03-12 12:22:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 17365.1 (4h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 92557
telemt_connections_bad_total 530
telemt_handshake_timeouts_total 3331
telemt_upstream_connect_attempt_total 4295
telemt_upstream_connect_success_total 4275
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 4295
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1922
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2347
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 206
telemt_me_reconnect_attempts_total 3376
telemt_me_reconnect_success_total 3355
telemt_me_reader_eof_total 3505
telemt_me_idle_close_by_peer_total 3504
telemt_me_route_drop_no_conn_total 25787
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 83307
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 390
telemt_desync_full_logged_total 149
telemt_desync_suppressed_total 241
telemt_desync_frames_bucket_total{bucket="1_2"} 76
telemt_desync_frames_bucket_total{bucket="3_10"} 156
telemt_desync_frames_bucket_total{bucket="gt_10"} 158
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 3376
telemt_me_writer_restored_same_endpoint_total 3339
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 83276
telemt_user_connections_current{user="hello"} 320
telemt_user_octets_from_client{user="hello"} 1151814388 (1.07 GB)
telemt_user_octets_to_client{user="hello"} 26914534288 (25.07 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 17258.2 (4h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36970
telemt_connections_bad_total 271
telemt_handshake_timeouts_total 303
telemt_upstream_connect_attempt_total 5364
telemt_upstream_connect_success_total 5233
telemt_upstream_connect_fail_total 131
telemt_upstream_connect_attempts_per_request{bucket="1"} 5364
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2135
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3087
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 131
telemt_me_keepalive_timeout_total 135
telemt_me_reconnect_attempts_total 18201
telemt_me_reconnect_success_total 4330
telemt_me_reader_eof_total 4806
telemt_me_idle_close_by_peer_total 4806
telemt_me_route_drop_no_conn_total 16162
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 35184
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
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
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 4779
telemt_me_refill_failed_total 433
telemt_me_writer_restored_same_endpoint_total 4315
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 449
telemt_user_connections_total{user="hello"} 35185
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 407864296 (388.97 MB)
telemt_user_octets_to_client{user="hello"} 9297985028 (8.66 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 17221.7 (4h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50506
telemt_connections_bad_total 127
telemt_handshake_timeouts_total 470
telemt_upstream_connect_attempt_total 4775
telemt_upstream_connect_success_total 4775
telemt_upstream_connect_attempts_per_request{bucket="1"} 4775
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2363
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2404
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 3874
telemt_me_reconnect_success_total 3848
telemt_me_reader_eof_total 4037
telemt_me_idle_close_by_peer_total 4037
telemt_me_route_drop_no_conn_total 17338
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 47556
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 3867
telemt_me_writer_restored_same_endpoint_total 3828
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 47540
telemt_user_connections_current{user="hello"} 157
telemt_user_octets_from_client{user="hello"} 1533249124 (1.43 GB)
telemt_user_octets_to_client{user="hello"} 31322063404 (29.17 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 17197.4 (4h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63888
telemt_connections_bad_total 1082
telemt_handshake_timeouts_total 306
telemt_upstream_connect_attempt_total 4679
telemt_upstream_connect_success_total 4567
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 4679
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2000
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2556
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_keepalive_timeout_total 180
telemt_me_reconnect_attempts_total 10195
telemt_me_reconnect_success_total 3655
telemt_me_reader_eof_total 3974
telemt_me_idle_close_by_peer_total 3974
telemt_me_route_drop_no_conn_total 21352
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 58448
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 179
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 116
telemt_desync_frames_bucket_total{bucket="1_2"} 72
telemt_desync_frames_bucket_total{bucket="3_10"} 59
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 3905
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 3647
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 250
telemt_user_connections_total{user="hello"} 58446
telemt_user_connections_current{user="hello"} 190
telemt_user_octets_from_client{user="hello"} 1046991264 (998.49 MB)
telemt_user_octets_to_client{user="hello"} 29577160900 (27.55 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 17166.8 (4h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34883
telemt_connections_bad_total 3250
telemt_handshake_timeouts_total 449
telemt_upstream_connect_attempt_total 4648
telemt_upstream_connect_success_total 4442
telemt_upstream_connect_fail_total 206
telemt_upstream_connect_attempts_per_request{bucket="1"} 4648
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1588
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2839
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 206
telemt_me_keepalive_timeout_total 97
telemt_me_reconnect_attempts_total 20356
telemt_me_reconnect_success_total 3551
telemt_me_reader_eof_total 4073
telemt_me_idle_close_by_peer_total 4073
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 10851
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 30278
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 378
telemt_desync_full_logged_total 110
telemt_desync_suppressed_total 268
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 309
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 4097
telemt_me_refill_failed_total 526
telemt_me_writer_restored_same_endpoint_total 3534
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 546
telemt_user_connections_total{user="hello"} 30275
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 211318772 (201.53 MB)
telemt_user_octets_to_client{user="hello"} 7632931152 (7.11 GB)
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 17153.8 (4h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95955
telemt_connections_bad_total 758
telemt_handshake_timeouts_total 898
telemt_upstream_connect_attempt_total 3423
telemt_upstream_connect_success_total 3407
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 3423
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1636
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1769
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 80
telemt_me_reconnect_attempts_total 2545
telemt_me_reconnect_success_total 2524
telemt_me_reader_eof_total 2653
telemt_me_idle_close_by_peer_total 2653
telemt_me_route_drop_no_conn_total 39682
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 91163
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 175
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 112
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 70
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 2554
telemt_me_writer_restored_same_endpoint_total 2517
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 91130
telemt_user_connections_current{user="hello"} 391
telemt_user_octets_from_client{user="hello"} 2381053436 (2.22 GB)
telemt_user_octets_to_client{user="hello"} 44965874688 (41.88 GB)
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 53
```