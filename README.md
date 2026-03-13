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

# Server Metrics 2026-03-13 16:11:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 117490.4 (32h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 488773
telemt_connections_bad_total 3577
telemt_handshake_timeouts_total 8895
telemt_upstream_connect_attempt_total 29280
telemt_upstream_connect_success_total 29138
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 29280
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13169
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15905
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2548
telemt_me_reconnect_attempts_total 26798
telemt_me_reconnect_success_total 23261
telemt_me_reader_eof_total 24851
telemt_me_idle_close_by_peer_total 24850
telemt_me_route_drop_no_conn_total 160186
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 429449
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1387
telemt_desync_full_logged_total 486
telemt_desync_suppressed_total 901
telemt_desync_frames_bucket_total{bucket="1_2"} 304
telemt_desync_frames_bucket_total{bucket="3_10"} 498
telemt_desync_frames_bucket_total{bucket="gt_10"} 585
telemt_pool_swap_total 107
telemt_me_writer_removed_unexpected_total 23616
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 23245
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 355
telemt_user_connections_total{user="hello"} 429021
telemt_user_connections_current{user="hello"} 347
telemt_user_octets_from_client{user="hello"} 7607720464 (7.09 GB)
telemt_user_octets_to_client{user="hello"} 200451951752 (186.69 GB)
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 117383.3 (32h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 237243
telemt_connections_bad_total 1883
telemt_handshake_timeouts_total 1716
telemt_upstream_connect_attempt_total 93551
telemt_upstream_connect_success_total 92756
telemt_upstream_connect_fail_total 795
telemt_upstream_connect_attempts_per_request{bucket="1"} 93551
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 66895
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24682
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1179
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 795
telemt_me_keepalive_timeout_total 1418
telemt_me_reconnect_attempts_total 117685
telemt_me_reconnect_success_total 26024
telemt_me_reader_eof_total 29644
telemt_me_idle_close_by_peer_total 29644
telemt_me_route_drop_no_conn_total 81791
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 163834
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 28
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
telemt_me_writer_removed_unexpected_total 29112
telemt_me_refill_failed_total 2860
telemt_me_writer_restored_same_endpoint_total 26007
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3088
telemt_user_connections_total{user="hello"} 224483
telemt_user_connections_current{user="hello"} 197
telemt_user_octets_from_client{user="hello"} 2332557218 (2.17 GB)
telemt_user_octets_to_client{user="hello"} 70002510898 (65.19 GB)
telemt_user_msgs_from_client{user="hello"} 937825
telemt_user_msgs_to_client{user="hello"} 5648477
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 117347.0 (32h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 284145
telemt_connections_bad_total 2441
telemt_handshake_timeouts_total 13891
telemt_upstream_connect_attempt_total 31389
telemt_upstream_connect_success_total 31385
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 31389
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14559
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16795
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2418
telemt_me_reconnect_attempts_total 26690
telemt_me_reconnect_success_total 25469
telemt_me_reader_eof_total 27302
telemt_me_idle_close_by_peer_total 27302
telemt_me_route_drop_no_conn_total 102497
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 257739
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 103
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_pool_swap_total 107
telemt_me_writer_removed_unexpected_total 25753
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 25449
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 284
telemt_user_connections_total{user="hello"} 257653
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 9688883456 (9.02 GB)
telemt_user_octets_to_client{user="hello"} 108849185644 (101.37 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 117322.4 (32h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 385268
telemt_connections_bad_total 15066
telemt_handshake_timeouts_total 3790
telemt_upstream_connect_attempt_total 43254
telemt_upstream_connect_success_total 33064
telemt_upstream_connect_fail_total 10190
telemt_upstream_connect_attempts_per_request{bucket="1"} 43254
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16629
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16215
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10190
telemt_me_keepalive_timeout_total 4176
telemt_me_reconnect_attempts_total 106970
telemt_me_reconnect_success_total 24144
telemt_me_reader_eof_total 27440
telemt_me_idle_close_by_peer_total 27433
telemt_me_route_drop_no_conn_total 138074
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 334589
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1350
telemt_desync_full_logged_total 402
telemt_desync_suppressed_total 948
telemt_desync_frames_bucket_total{bucket="1_2"} 331
telemt_desync_frames_bucket_total{bucket="3_10"} 520
telemt_desync_frames_bucket_total{bucket="gt_10"} 499
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 27039
telemt_me_refill_failed_total 2583
telemt_me_writer_restored_same_endpoint_total 24134
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2895
telemt_user_connections_total{user="hello"} 337503
telemt_user_connections_current{user="hello"} 219
telemt_user_octets_from_client{user="hello"} 7029122870 (6.55 GB)
telemt_user_octets_to_client{user="hello"} 125010559649 (116.43 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 67493.9 (18h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 106898
telemt_connections_bad_total 13927
telemt_handshake_timeouts_total 1327
telemt_upstream_connect_attempt_total 27149
telemt_upstream_connect_success_total 26912
telemt_upstream_connect_fail_total 237
telemt_upstream_connect_attempts_per_request{bucket="1"} 27149
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14012
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12822
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 237
telemt_me_keepalive_timeout_total 1060
telemt_me_reconnect_attempts_total 29821
telemt_me_reconnect_success_total 18648
telemt_me_reader_eof_total 19985
telemt_me_idle_close_by_peer_total 19985
telemt_me_route_drop_no_conn_total 32766
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 83307
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 390
telemt_desync_full_logged_total 76
telemt_desync_suppressed_total 314
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 214
telemt_desync_frames_bucket_total{bucket="gt_10"} 124
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 19158
telemt_me_refill_failed_total 347
telemt_me_writer_restored_same_endpoint_total 18630
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 510
telemt_user_connections_total{user="hello"} 88206
telemt_user_connections_current{user="hello"} 87
telemt_user_octets_from_client{user="hello"} 1012923441 (966.00 MB)
telemt_user_octets_to_client{user="hello"} 26999512199 (25.15 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 117279.5 (32h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 712664
telemt_connections_bad_total 24632
telemt_handshake_timeouts_total 23864
telemt_upstream_connect_attempt_total 24548
telemt_upstream_connect_success_total 24425
telemt_upstream_connect_fail_total 123
telemt_upstream_connect_attempts_per_request{bucket="1"} 24548
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11472
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12928
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 123
telemt_me_keepalive_timeout_total 2565
telemt_me_reconnect_attempts_total 23216
telemt_me_reconnect_success_total 18586
telemt_me_reader_eof_total 19948
telemt_me_idle_close_by_peer_total 19945
telemt_me_route_drop_no_conn_total 336382
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 667866
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 667
telemt_desync_full_logged_total 217
telemt_desync_suppressed_total 450
telemt_desync_frames_bucket_total{bucket="1_2"} 236
telemt_desync_frames_bucket_total{bucket="3_10"} 221
telemt_desync_frames_bucket_total{bucket="gt_10"} 210
telemt_pool_swap_total 109
telemt_me_writer_removed_unexpected_total 18968
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 18579
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 382
telemt_user_connections_total{user="hello"} 640769
telemt_user_connections_current{user="hello"} 453
telemt_user_octets_from_client{user="hello"} 11175044032 (10.41 GB)
telemt_user_octets_to_client{user="hello"} 329135462236 (306.53 GB)
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 83
```