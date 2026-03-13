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

# Server Metrics 2026-03-13 12:37:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 104645.0 (29h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 427865
telemt_connections_bad_total 3211
telemt_handshake_timeouts_total 8386
telemt_upstream_connect_attempt_total 26598
telemt_upstream_connect_success_total 26472
telemt_upstream_connect_fail_total 126
telemt_upstream_connect_attempts_per_request{bucket="1"} 26598
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11949
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14475
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 126
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2395
telemt_me_reconnect_attempts_total 24736
telemt_me_reconnect_success_total 21211
telemt_me_reader_eof_total 22648
telemt_me_idle_close_by_peer_total 22647
telemt_me_route_drop_no_conn_total 135408
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 371909
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1253
telemt_desync_full_logged_total 445
telemt_desync_suppressed_total 808
telemt_desync_frames_bucket_total{bucket="1_2"} 253
telemt_desync_frames_bucket_total{bucket="3_10"} 462
telemt_desync_frames_bucket_total{bucket="gt_10"} 538
telemt_pool_swap_total 93
telemt_me_writer_removed_unexpected_total 21540
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 21195
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 329
telemt_user_connections_total{user="hello"} 371501
telemt_user_connections_current{user="hello"} 335
telemt_user_octets_from_client{user="hello"} 6640521940 (6.18 GB)
telemt_user_octets_to_client{user="hello"} 159397442720 (148.45 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 104538.6 (29h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 197701
telemt_connections_bad_total 1659
telemt_handshake_timeouts_total 1481
telemt_upstream_connect_attempt_total 59372
telemt_upstream_connect_success_total 58664
telemt_upstream_connect_fail_total 708
telemt_upstream_connect_attempts_per_request{bucket="1"} 59372
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37166
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20917
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 581
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 708
telemt_me_keepalive_timeout_total 1367
telemt_me_reconnect_attempts_total 97199
telemt_me_reconnect_success_total 25958
telemt_me_reader_eof_total 28944
telemt_me_idle_close_by_peer_total 28944
telemt_me_route_drop_no_conn_total 79177
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 159287
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 23
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
telemt_me_writer_removed_unexpected_total 28408
telemt_me_refill_failed_total 2222
telemt_me_writer_restored_same_endpoint_total 25941
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2450
telemt_user_connections_total{user="hello"} 186526
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 1894362071 (1.76 GB)
telemt_user_octets_to_client{user="hello"} 61462180232 (57.24 GB)
telemt_user_msgs_from_client{user="hello"} 408295
telemt_user_msgs_to_client{user="hello"} 2973005
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 104502.5 (29h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 240243
telemt_connections_bad_total 2065
telemt_handshake_timeouts_total 7920
telemt_upstream_connect_attempt_total 28336
telemt_upstream_connect_success_total 28332
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 28336
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13121
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15184
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2202
telemt_me_reconnect_attempts_total 24246
telemt_me_reconnect_success_total 23035
telemt_me_reader_eof_total 24672
telemt_me_idle_close_by_peer_total 24672
telemt_me_route_drop_no_conn_total 89025
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 221556
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 92
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 94
telemt_me_writer_removed_unexpected_total 23288
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 23015
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 253
telemt_user_connections_total{user="hello"} 221470
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 9387930756 (8.74 GB)
telemt_user_octets_to_client{user="hello"} 98110130152 (91.37 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 104477.9 (29h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 335737
telemt_connections_bad_total 14997
telemt_handshake_timeouts_total 2488
telemt_upstream_connect_attempt_total 40107
telemt_upstream_connect_success_total 30031
telemt_upstream_connect_fail_total 10076
telemt_upstream_connect_attempts_per_request{bucket="1"} 40107
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15162
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14657
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 203
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10076
telemt_me_keepalive_timeout_total 4071
telemt_me_reconnect_attempts_total 93295
telemt_me_reconnect_success_total 21743
telemt_me_reader_eof_total 24632
telemt_me_idle_close_by_peer_total 24625
telemt_me_route_drop_no_conn_total 120857
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 289091
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1025
telemt_desync_full_logged_total 303
telemt_desync_suppressed_total 722
telemt_desync_frames_bucket_total{bucket="1_2"} 250
telemt_desync_frames_bucket_total{bucket="3_10"} 382
telemt_desync_frames_bucket_total{bucket="gt_10"} 393
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 24249
telemt_me_refill_failed_total 2231
telemt_me_writer_restored_same_endpoint_total 21733
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2506
telemt_user_connections_total{user="hello"} 292002
telemt_user_connections_current{user="hello"} 221
telemt_user_octets_from_client{user="hello"} 5969310918 (5.56 GB)
telemt_user_octets_to_client{user="hello"} 110028582125 (102.47 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 54649.4 (15h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80007
telemt_connections_bad_total 10789
telemt_handshake_timeouts_total 1173
telemt_upstream_connect_attempt_total 23540
telemt_upstream_connect_success_total 23355
telemt_upstream_connect_fail_total 185
telemt_upstream_connect_attempts_per_request{bucket="1"} 23540
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12406
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10886
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 185
telemt_me_keepalive_timeout_total 958
telemt_me_reconnect_attempts_total 25622
telemt_me_reconnect_success_total 15705
telemt_me_reader_eof_total 16860
telemt_me_idle_close_by_peer_total 16860
telemt_me_route_drop_no_conn_total 23589
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 60551
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 123
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 102
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 16153
telemt_me_refill_failed_total 308
telemt_me_writer_restored_same_endpoint_total 15687
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 448
telemt_user_connections_total{user="hello"} 65460
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 565451233 (539.26 MB)
telemt_user_octets_to_client{user="hello"} 18242901859 (16.99 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 104434.3 (29h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 598356
telemt_connections_bad_total 17585
telemt_handshake_timeouts_total 14782
telemt_upstream_connect_attempt_total 22142
telemt_upstream_connect_success_total 22027
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 22142
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10332
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11670
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_keepalive_timeout_total 2500
telemt_me_reconnect_attempts_total 21457
telemt_me_reconnect_success_total 16835
telemt_me_reader_eof_total 18065
telemt_me_idle_close_by_peer_total 18062
telemt_me_route_drop_no_conn_total 293711
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 572534
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 471
telemt_desync_full_logged_total 176
telemt_desync_suppressed_total 295
telemt_desync_frames_bucket_total{bucket="1_2"} 110
telemt_desync_frames_bucket_total{bucket="3_10"} 177
telemt_desync_frames_bucket_total{bucket="gt_10"} 184
telemt_pool_swap_total 95
telemt_me_writer_removed_unexpected_total 17197
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 16828
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 362
telemt_user_connections_total{user="hello"} 545594
telemt_user_connections_current{user="hello"} 411
telemt_user_octets_from_client{user="hello"} 9638036444 (8.98 GB)
telemt_user_octets_to_client{user="hello"} 290090317808 (270.17 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 54
```