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

# Server Metrics 2026-03-12 11:57:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 15831.8 (4h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84631
telemt_connections_bad_total 527
telemt_handshake_timeouts_total 3138
telemt_upstream_connect_attempt_total 3861
telemt_upstream_connect_success_total 3844
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 3861
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1723
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2115
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 181
telemt_me_reconnect_attempts_total 3035
telemt_me_reconnect_success_total 3017
telemt_me_reader_eof_total 3148
telemt_me_idle_close_by_peer_total 3147
telemt_me_route_drop_no_conn_total 23257
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 76246
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 336
telemt_desync_full_logged_total 130
telemt_desync_suppressed_total 206
telemt_desync_frames_bucket_total{bucket="1_2"} 68
telemt_desync_frames_bucket_total{bucket="3_10"} 130
telemt_desync_frames_bucket_total{bucket="gt_10"} 138
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 3035
telemt_me_writer_restored_same_endpoint_total 3001
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 76213
telemt_user_connections_current{user="hello"} 335
telemt_user_octets_from_client{user="hello"} 1077628620 (1.00 GB)
telemt_user_octets_to_client{user="hello"} 25530407336 (23.78 GB)
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 15725.1 (4h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33708
telemt_connections_bad_total 270
telemt_handshake_timeouts_total 278
telemt_upstream_connect_attempt_total 5078
telemt_upstream_connect_success_total 4969
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 5078
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1988
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2971
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 127
telemt_me_reconnect_attempts_total 15912
telemt_me_reconnect_success_total 4154
telemt_me_reader_eof_total 4563
telemt_me_idle_close_by_peer_total 4563
telemt_me_route_drop_no_conn_total 14595
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 32040
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 3
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
telemt_me_writer_removed_unexpected_total 4535
telemt_me_refill_failed_total 367
telemt_me_writer_restored_same_endpoint_total 4139
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 381
telemt_user_connections_total{user="hello"} 32041
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 367910760 (350.87 MB)
telemt_user_octets_to_client{user="hello"} 8406405992 (7.83 GB)
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 15688.8 (4h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46204
telemt_connections_bad_total 123
telemt_handshake_timeouts_total 408
telemt_upstream_connect_attempt_total 4329
telemt_upstream_connect_success_total 4329
telemt_upstream_connect_attempts_per_request{bucket="1"} 4329
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2124
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2198
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 3519
telemt_me_reconnect_success_total 3495
telemt_me_reader_eof_total 3675
telemt_me_idle_close_by_peer_total 3675
telemt_me_route_drop_no_conn_total 15708
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 43429
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
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 3510
telemt_me_writer_restored_same_endpoint_total 3475
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 43415
telemt_user_connections_current{user="hello"} 163
telemt_user_octets_from_client{user="hello"} 1499580896 (1.40 GB)
telemt_user_octets_to_client{user="hello"} 30930421696 (28.81 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 15664.3 (4h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56932
telemt_connections_bad_total 1081
telemt_handshake_timeouts_total 295
telemt_upstream_connect_attempt_total 4459
telemt_upstream_connect_success_total 4350
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 4459
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1879
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2461
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 175
telemt_me_reconnect_attempts_total 8684
telemt_me_reconnect_success_total 3521
telemt_me_reader_eof_total 3797
telemt_me_idle_close_by_peer_total 3797
telemt_me_route_drop_no_conn_total 18826
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 51980
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 175
telemt_desync_full_logged_total 62
telemt_desync_suppressed_total 113
telemt_desync_frames_bucket_total{bucket="1_2"} 72
telemt_desync_frames_bucket_total{bucket="3_10"} 57
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 3728
telemt_me_refill_failed_total 160
telemt_me_writer_restored_same_endpoint_total 3513
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 207
telemt_user_connections_total{user="hello"} 51979
telemt_user_connections_current{user="hello"} 217
telemt_user_octets_from_client{user="hello"} 1010496192 (963.68 MB)
telemt_user_octets_to_client{user="hello"} 27947588636 (26.03 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 15633.9 (4h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31434
telemt_connections_bad_total 2965
telemt_handshake_timeouts_total 426
telemt_upstream_connect_attempt_total 4487
telemt_upstream_connect_success_total 4288
telemt_upstream_connect_fail_total 199
telemt_upstream_connect_attempts_per_request{bucket="1"} 4487
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1528
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2746
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 199
telemt_me_keepalive_timeout_total 94
telemt_me_reconnect_attempts_total 18893
telemt_me_reconnect_success_total 3464
telemt_me_reader_eof_total 3943
telemt_me_idle_close_by_peer_total 3943
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 9426
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 27197
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 375
telemt_desync_full_logged_total 109
telemt_desync_suppressed_total 266
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 3967
telemt_me_refill_failed_total 483
telemt_me_writer_restored_same_endpoint_total 3447
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 503
telemt_user_connections_total{user="hello"} 27194
telemt_user_connections_current{user="hello"} 133
telemt_user_octets_from_client{user="hello"} 181046560 (172.66 MB)
telemt_user_octets_to_client{user="hello"} 7069067512 (6.58 GB)
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 15620.7 (4h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85501
telemt_connections_bad_total 748
telemt_handshake_timeouts_total 831
telemt_upstream_connect_attempt_total 3155
telemt_upstream_connect_success_total 3139
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 3155
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1519
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1618
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 2341
telemt_me_reconnect_success_total 2323
telemt_me_reader_eof_total 2442
telemt_me_idle_close_by_peer_total 2442
telemt_me_route_drop_no_conn_total 35517
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 81056
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 173
telemt_desync_full_logged_total 61
telemt_desync_suppressed_total 112
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 70
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 2350
telemt_me_writer_restored_same_endpoint_total 2316
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 81023
telemt_user_connections_current{user="hello"} 384
telemt_user_octets_from_client{user="hello"} 2211897956 (2.06 GB)
telemt_user_octets_to_client{user="hello"} 40261661848 (37.50 GB)
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 57
```