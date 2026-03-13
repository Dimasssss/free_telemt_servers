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

# Server Metrics 2026-03-13 13:28:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 107698.6 (29h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 443346
telemt_connections_bad_total 3214
telemt_handshake_timeouts_total 8469
telemt_upstream_connect_attempt_total 27232
telemt_upstream_connect_success_total 27104
telemt_upstream_connect_fail_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 27232
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12241
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14805
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 128
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2407
telemt_me_reconnect_attempts_total 25239
telemt_me_reconnect_success_total 21712
telemt_me_reader_eof_total 23186
telemt_me_idle_close_by_peer_total 23185
telemt_me_route_drop_no_conn_total 142119
telemt_me_route_drop_channel_closed_total 26
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 386669
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1298
telemt_desync_full_logged_total 460
telemt_desync_suppressed_total 838
telemt_desync_frames_bucket_total{bucket="1_2"} 278
telemt_desync_frames_bucket_total{bucket="3_10"} 475
telemt_desync_frames_bucket_total{bucket="gt_10"} 545
telemt_pool_swap_total 96
telemt_me_writer_removed_unexpected_total 22048
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 21696
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 336
telemt_user_connections_total{user="hello"} 386251
telemt_user_connections_current{user="hello"} 339
telemt_user_octets_from_client{user="hello"} 7041166696 (6.56 GB)
telemt_user_octets_to_client{user="hello"} 170141072316 (158.46 GB)
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 107592.2 (29h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 206806
telemt_connections_bad_total 1680
telemt_handshake_timeouts_total 1517
telemt_upstream_connect_attempt_total 67042
telemt_upstream_connect_success_total 66317
telemt_upstream_connect_fail_total 725
telemt_upstream_connect_attempts_per_request{bucket="1"} 67042
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43949
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21736
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 632
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 725
telemt_me_keepalive_timeout_total 1387
telemt_me_reconnect_attempts_total 102517
telemt_me_reconnect_success_total 25995
telemt_me_reader_eof_total 29146
telemt_me_idle_close_by_peer_total 29146
telemt_me_route_drop_no_conn_total 79753
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 160552
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 24
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
telemt_me_writer_removed_unexpected_total 28610
telemt_me_refill_failed_total 2387
telemt_me_writer_restored_same_endpoint_total 25978
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2615
telemt_user_connections_total{user="hello"} 195277
telemt_user_connections_current{user="hello"} 195
telemt_user_octets_from_client{user="hello"} 2000822203 (1.86 GB)
telemt_user_octets_to_client{user="hello"} 63657104912 (59.29 GB)
telemt_user_msgs_from_client{user="hello"} 525215
telemt_user_msgs_to_client{user="hello"} 3699878
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 107555.8 (29h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 251711
telemt_connections_bad_total 2075
telemt_handshake_timeouts_total 9719
telemt_upstream_connect_attempt_total 29018
telemt_upstream_connect_success_total 29014
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 29018
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13455
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15532
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2249
telemt_me_reconnect_attempts_total 24798
telemt_me_reconnect_success_total 23585
telemt_me_reader_eof_total 25268
telemt_me_idle_close_by_peer_total 25268
telemt_me_route_drop_no_conn_total 92048
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 230833
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
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 23841
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 23565
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 256
telemt_user_connections_total{user="hello"} 230749
telemt_user_connections_current{user="hello"} 168
telemt_user_octets_from_client{user="hello"} 9447892072 (8.80 GB)
telemt_user_octets_to_client{user="hello"} 99805510972 (92.95 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 107531.5 (29h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 349127
telemt_connections_bad_total 15028
telemt_handshake_timeouts_total 3413
telemt_upstream_connect_attempt_total 40952
telemt_upstream_connect_success_total 30842
telemt_upstream_connect_fail_total 10110
telemt_upstream_connect_attempts_per_request{bucket="1"} 40952
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15587
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15040
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 206
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10110
telemt_me_keepalive_timeout_total 4126
telemt_me_reconnect_attempts_total 94891
telemt_me_reconnect_success_total 22408
telemt_me_reader_eof_total 25348
telemt_me_idle_close_by_peer_total 25341
telemt_me_route_drop_no_conn_total 125044
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 300506
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1116
telemt_desync_full_logged_total 328
telemt_desync_suppressed_total 788
telemt_desync_frames_bucket_total{bucket="1_2"} 273
telemt_desync_frames_bucket_total{bucket="3_10"} 424
telemt_desync_frames_bucket_total{bucket="gt_10"} 419
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 24958
telemt_me_refill_failed_total 2260
telemt_me_writer_restored_same_endpoint_total 22398
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2550
telemt_user_connections_total{user="hello"} 303417
telemt_user_connections_current{user="hello"} 257
telemt_user_octets_from_client{user="hello"} 6629071342 (6.17 GB)
telemt_user_octets_to_client{user="hello"} 113974546105 (106.15 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 57703.0 (16h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85931
telemt_connections_bad_total 11392
telemt_handshake_timeouts_total 1202
telemt_upstream_connect_attempt_total 24330
telemt_upstream_connect_success_total 24133
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 24330
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12741
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11326
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_timeout_total 996
telemt_me_reconnect_attempts_total 26232
telemt_me_reconnect_success_total 16313
telemt_me_reader_eof_total 17507
telemt_me_idle_close_by_peer_total 17507
telemt_me_route_drop_no_conn_total 25712
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 65675
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 178
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 146
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 78
telemt_desync_frames_bucket_total{bucket="gt_10"} 73
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 16764
telemt_me_refill_failed_total 308
telemt_me_writer_restored_same_endpoint_total 16295
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 451
telemt_user_connections_total{user="hello"} 70575
telemt_user_connections_current{user="hello"} 133
telemt_user_octets_from_client{user="hello"} 864318817 (824.28 MB)
telemt_user_octets_to_client{user="hello"} 20347421951 (18.95 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 107488.1 (29h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 624152
telemt_connections_bad_total 17929
telemt_handshake_timeouts_total 17299
telemt_upstream_connect_attempt_total 22742
telemt_upstream_connect_success_total 22625
telemt_upstream_connect_fail_total 117
telemt_upstream_connect_attempts_per_request{bucket="1"} 22742
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10605
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11995
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 117
telemt_me_keepalive_timeout_total 2504
telemt_me_reconnect_attempts_total 21893
telemt_me_reconnect_success_total 17269
telemt_me_reader_eof_total 18541
telemt_me_idle_close_by_peer_total 18538
telemt_me_route_drop_no_conn_total 304372
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 594713
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 472
telemt_desync_full_logged_total 177
telemt_desync_suppressed_total 295
telemt_desync_frames_bucket_total{bucket="1_2"} 111
telemt_desync_frames_bucket_total{bucket="3_10"} 177
telemt_desync_frames_bucket_total{bucket="gt_10"} 184
telemt_pool_swap_total 99
telemt_me_writer_removed_unexpected_total 17637
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 17262
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 368
telemt_user_connections_total{user="hello"} 567758
telemt_user_connections_current{user="hello"} 390
telemt_user_octets_from_client{user="hello"} 9923631648 (9.24 GB)
telemt_user_octets_to_client{user="hello"} 302142805612 (281.39 GB)
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 57
```