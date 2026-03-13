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

# Server Metrics 2026-03-13 14:49:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 112585.2 (31h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 466245
telemt_connections_bad_total 3227
telemt_handshake_timeouts_total 8645
telemt_upstream_connect_attempt_total 28279
telemt_upstream_connect_success_total 28142
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 28279
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12697
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15382
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2428
telemt_me_reconnect_attempts_total 26028
telemt_me_reconnect_success_total 22496
telemt_me_reader_eof_total 24026
telemt_me_idle_close_by_peer_total 24025
telemt_me_route_drop_no_conn_total 151886
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 408566
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1347
telemt_desync_full_logged_total 477
telemt_desync_suppressed_total 870
telemt_desync_frames_bucket_total{bucket="1_2"} 295
telemt_desync_frames_bucket_total{bucket="3_10"} 487
telemt_desync_frames_bucket_total{bucket="gt_10"} 565
telemt_pool_swap_total 101
telemt_me_writer_removed_unexpected_total 22840
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 22480
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 344
telemt_user_connections_total{user="hello"} 408143
telemt_user_connections_current{user="hello"} 338
telemt_user_octets_from_client{user="hello"} 7347518320 (6.84 GB)
telemt_user_octets_to_client{user="hello"} 188901997020 (175.93 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 112477.9 (31h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 221569
telemt_connections_bad_total 1830
telemt_handshake_timeouts_total 1577
telemt_upstream_connect_attempt_total 79675
telemt_upstream_connect_success_total 78922
telemt_upstream_connect_fail_total 753
telemt_upstream_connect_attempts_per_request{bucket="1"} 79675
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55052
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23102
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 768
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 753
telemt_me_keepalive_timeout_total 1399
telemt_me_reconnect_attempts_total 109426
telemt_me_reconnect_success_total 26022
telemt_me_reader_eof_total 29388
telemt_me_idle_close_by_peer_total 29388
telemt_me_route_drop_no_conn_total 80277
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 162283
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 26
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
telemt_me_writer_removed_unexpected_total 28852
telemt_me_refill_failed_total 2602
telemt_me_writer_restored_same_endpoint_total 26005
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2830
telemt_user_connections_total{user="hello"} 209366
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 2105008987 (1.96 GB)
telemt_user_octets_to_client{user="hello"} 66727102784 (62.14 GB)
telemt_user_msgs_from_client{user="hello"} 693645
telemt_user_msgs_to_client{user="hello"} 4661899
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 112441.5 (31h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 268082
telemt_connections_bad_total 2268
telemt_handshake_timeouts_total 11759
telemt_upstream_connect_attempt_total 30264
telemt_upstream_connect_success_total 30260
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 30264
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14020
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16209
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2292
telemt_me_reconnect_attempts_total 25827
telemt_me_reconnect_success_total 24609
telemt_me_reader_eof_total 26361
telemt_me_idle_close_by_peer_total 26361
telemt_me_route_drop_no_conn_total 96987
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 244475
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 96
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 51
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 101
telemt_me_writer_removed_unexpected_total 24877
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 24589
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 268
telemt_user_connections_total{user="hello"} 244390
telemt_user_connections_current{user="hello"} 143
telemt_user_octets_from_client{user="hello"} 9524515376 (8.87 GB)
telemt_user_octets_to_client{user="hello"} 105225350588 (98.00 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 112417.1 (31h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 367470
telemt_connections_bad_total 15044
telemt_handshake_timeouts_total 3649
telemt_upstream_connect_attempt_total 42287
telemt_upstream_connect_success_total 32145
telemt_upstream_connect_fail_total 10142
telemt_upstream_connect_attempts_per_request{bucket="1"} 42287
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16221
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15704
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10142
telemt_me_keepalive_timeout_total 4146
telemt_me_reconnect_attempts_total 98280
telemt_me_reconnect_success_total 23490
telemt_me_reader_eof_total 26531
telemt_me_idle_close_by_peer_total 26524
telemt_me_route_drop_no_conn_total 131698
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 317755
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1228
telemt_desync_full_logged_total 363
telemt_desync_suppressed_total 865
telemt_desync_frames_bucket_total{bucket="1_2"} 303
telemt_desync_frames_bucket_total{bucket="3_10"} 460
telemt_desync_frames_bucket_total{bucket="gt_10"} 465
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 26129
telemt_me_refill_failed_total 2332
telemt_me_writer_restored_same_endpoint_total 23480
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2639
telemt_user_connections_total{user="hello"} 320665
telemt_user_connections_current{user="hello"} 234
telemt_user_octets_from_client{user="hello"} 6857816438 (6.39 GB)
telemt_user_octets_to_client{user="hello"} 120820658525 (112.52 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 62588.5 (17h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 96287
telemt_connections_bad_total 12569
telemt_handshake_timeouts_total 1217
telemt_upstream_connect_attempt_total 25691
telemt_upstream_connect_success_total 25476
telemt_upstream_connect_fail_total 215
telemt_upstream_connect_attempts_per_request{bucket="1"} 25691
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13336
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12070
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 215
telemt_me_keepalive_timeout_total 1034
telemt_me_reconnect_attempts_total 27354
telemt_me_reconnect_success_total 17431
telemt_me_reader_eof_total 18688
telemt_me_idle_close_by_peer_total 18688
telemt_me_route_drop_no_conn_total 28724
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 74531
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 332
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 265
telemt_desync_frames_bucket_total{bucket="1_2"} 41
telemt_desync_frames_bucket_total{bucket="3_10"} 174
telemt_desync_frames_bucket_total{bucket="gt_10"} 117
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 17892
telemt_me_refill_failed_total 308
telemt_me_writer_restored_same_endpoint_total 17413
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 461
telemt_user_connections_total{user="hello"} 79430
telemt_user_connections_current{user="hello"} 135
telemt_user_octets_from_client{user="hello"} 930094713 (887.01 MB)
telemt_user_octets_to_client{user="hello"} 23554108507 (21.94 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 112373.9 (31h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 667207
telemt_connections_bad_total 19218
telemt_handshake_timeouts_total 21171
telemt_upstream_connect_attempt_total 23636
telemt_upstream_connect_success_total 23518
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 23636
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11017
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12476
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 2532
telemt_me_reconnect_attempts_total 22570
telemt_me_reconnect_success_total 17944
telemt_me_reader_eof_total 19253
telemt_me_idle_close_by_peer_total 19250
telemt_me_route_drop_no_conn_total 320331
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 631524
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 481
telemt_desync_full_logged_total 182
telemt_desync_suppressed_total 299
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 178
telemt_desync_frames_bucket_total{bucket="gt_10"} 189
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 18319
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 17937
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 375
telemt_user_connections_total{user="hello"} 604476
telemt_user_connections_current{user="hello"} 524
telemt_user_octets_from_client{user="hello"} 10404980724 (9.69 GB)
telemt_user_octets_to_client{user="hello"} 315713549660 (294.03 GB)
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 71
```