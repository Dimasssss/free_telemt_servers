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

# Server Metrics 2026-03-12 13:54:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 22880.6 (6h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 121249
telemt_connections_bad_total 1360
telemt_handshake_timeouts_total 4321
telemt_upstream_connect_attempt_total 5585
telemt_upstream_connect_success_total 5561
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 5585
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2487
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3068
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 248
telemt_me_reconnect_attempts_total 4396
telemt_me_reconnect_success_total 4367
telemt_me_reader_eof_total 4577
telemt_me_idle_close_by_peer_total 4576
telemt_me_route_drop_no_conn_total 33962
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 106422
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 522
telemt_desync_full_logged_total 191
telemt_desync_suppressed_total 331
telemt_desync_frames_bucket_total{bucket="1_2"} 97
telemt_desync_frames_bucket_total{bucket="3_10"} 203
telemt_desync_frames_bucket_total{bucket="gt_10"} 222
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 4404
telemt_me_writer_restored_same_endpoint_total 4351
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 106386
telemt_user_connections_current{user="hello"} 330
telemt_user_octets_from_client{user="hello"} 1714638208 (1.60 GB)
telemt_user_octets_to_client{user="hello"} 40648217884 (37.86 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 22774.0 (6h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49142
telemt_connections_bad_total 339
telemt_handshake_timeouts_total 346
telemt_upstream_connect_attempt_total 6735
telemt_upstream_connect_success_total 6575
telemt_upstream_connect_fail_total 160
telemt_upstream_connect_attempts_per_request{bucket="1"} 6735
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2738
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3817
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 160
telemt_me_keepalive_timeout_total 155
telemt_me_reconnect_attempts_total 21233
telemt_me_reconnect_success_total 5401
telemt_me_reader_eof_total 6005
telemt_me_idle_close_by_peer_total 6005
telemt_me_route_drop_no_conn_total 21805
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 46933
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 5
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
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 5926
telemt_me_refill_failed_total 494
telemt_me_writer_restored_same_endpoint_total 5386
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 525
telemt_user_connections_total{user="hello"} 46930
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 562463612 (536.41 MB)
telemt_user_octets_to_client{user="hello"} 13510747336 (12.58 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 22737.4 (6h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66722
telemt_connections_bad_total 138
telemt_handshake_timeouts_total 803
telemt_upstream_connect_attempt_total 6192
telemt_upstream_connect_success_total 6192
telemt_upstream_connect_attempts_per_request{bucket="1"} 6192
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3010
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3173
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 108
telemt_me_reconnect_attempts_total 5023
telemt_me_reconnect_success_total 4985
telemt_me_reader_eof_total 5273
telemt_me_idle_close_by_peer_total 5273
telemt_me_route_drop_no_conn_total 23322
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 62797
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
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 5021
telemt_me_writer_restored_same_endpoint_total 4965
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 62779
telemt_user_connections_current{user="hello"} 174
telemt_user_octets_from_client{user="hello"} 1829052376 (1.70 GB)
telemt_user_octets_to_client{user="hello"} 35876764388 (33.41 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 22713.2 (6h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86163
telemt_connections_bad_total 1509
telemt_handshake_timeouts_total 410
telemt_upstream_connect_attempt_total 6151
telemt_upstream_connect_success_total 5993
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 6151
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2643
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3329
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_keepalive_timeout_total 237
telemt_me_reconnect_attempts_total 16595
telemt_me_reconnect_success_total 4800
telemt_me_reader_eof_total 5298
telemt_me_idle_close_by_peer_total 5298
telemt_me_route_drop_no_conn_total 32238
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 79148
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 245
telemt_desync_full_logged_total 84
telemt_desync_suppressed_total 161
telemt_desync_frames_bucket_total{bucket="1_2"} 86
telemt_desync_frames_bucket_total{bucket="3_10"} 81
telemt_desync_frames_bucket_total{bucket="gt_10"} 78
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 5223
telemt_me_refill_failed_total 367
telemt_me_writer_restored_same_endpoint_total 4792
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 423
telemt_user_connections_total{user="hello"} 79031
telemt_user_connections_current{user="hello"} 176
telemt_user_octets_from_client{user="hello"} 1296131136 (1.21 GB)
telemt_user_octets_to_client{user="hello"} 34734879940 (32.35 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 22682.7 (6h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50230
telemt_connections_bad_total 4264
telemt_handshake_timeouts_total 683
telemt_upstream_connect_attempt_total 16865
telemt_upstream_connect_success_total 16576
telemt_upstream_connect_fail_total 288
telemt_upstream_connect_attempts_per_request{bucket="1"} 16864
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12784
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3767
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 288
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 29331
telemt_me_reconnect_success_total 3673
telemt_me_reader_eof_total 4471
telemt_me_idle_close_by_peer_total 4471
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 12074
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 32352
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 439
telemt_desync_full_logged_total 121
telemt_desync_suppressed_total 318
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 365
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 4496
telemt_me_refill_failed_total 803
telemt_me_writer_restored_same_endpoint_total 3656
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 823
telemt_user_connections_total{user="hello"} 44064
telemt_user_connections_current{user="hello"} 118
telemt_user_octets_from_client{user="hello"} 361740617 (344.98 MB)
telemt_user_octets_to_client{user="hello"} 11437077812 (10.65 GB)
telemt_user_msgs_from_client{user="hello"} 165225
telemt_user_msgs_to_client{user="hello"} 471849
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 22669.6 (6h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 134681
telemt_connections_bad_total 774
telemt_handshake_timeouts_total 1003
telemt_upstream_connect_attempt_total 4672
telemt_upstream_connect_success_total 4649
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 4672
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2214
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2433
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 111
telemt_me_reconnect_attempts_total 3497
telemt_me_reconnect_success_total 3467
telemt_me_reader_eof_total 3652
telemt_me_idle_close_by_peer_total 3652
telemt_me_route_drop_no_conn_total 53652
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 128657
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 222
telemt_desync_full_logged_total 78
telemt_desync_suppressed_total 144
telemt_desync_frames_bucket_total{bucket="1_2"} 53
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 82
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 3510
telemt_me_writer_restored_same_endpoint_total 3460
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 128624
telemt_user_connections_current{user="hello"} 398
telemt_user_octets_from_client{user="hello"} 2769257860 (2.58 GB)
telemt_user_octets_to_client{user="hello"} 53979196036 (50.27 GB)
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 47
```