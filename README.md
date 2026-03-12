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

# Server Metrics 2026-03-12 16:28:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 32094.6 (8h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 169568
telemt_connections_bad_total 2037
telemt_handshake_timeouts_total 4815
telemt_upstream_connect_attempt_total 7947
telemt_upstream_connect_success_total 7917
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 7947
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3510
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4400
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 308
telemt_me_reconnect_attempts_total 7400
telemt_me_reconnect_success_total 6266
telemt_me_reader_eof_total 6609
telemt_me_idle_close_by_peer_total 6608
telemt_me_route_drop_no_conn_total 49500
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 145176
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 621
telemt_desync_full_logged_total 231
telemt_desync_suppressed_total 390
telemt_desync_frames_bucket_total{bucket="1_2"} 117
telemt_desync_frames_bucket_total{bucket="3_10"} 237
telemt_desync_frames_bucket_total{bucket="gt_10"} 267
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 6362
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 6250
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 145136
telemt_user_connections_current{user="hello"} 342
telemt_user_octets_from_client{user="hello"} 2440099124 (2.27 GB)
telemt_user_octets_to_client{user="hello"} 56359691428 (52.49 GB)
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 31987.5 (8h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71056
telemt_connections_bad_total 464
telemt_handshake_timeouts_total 599
telemt_upstream_connect_attempt_total 10276
telemt_upstream_connect_success_total 10063
telemt_upstream_connect_fail_total 213
telemt_upstream_connect_attempts_per_request{bucket="1"} 10276
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3985
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6010
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 213
telemt_me_keepalive_timeout_total 267
telemt_me_reconnect_attempts_total 30358
telemt_me_reconnect_success_total 8438
telemt_me_reader_eof_total 9286
telemt_me_idle_close_by_peer_total 9286
telemt_me_route_drop_no_conn_total 31294
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 67496
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 7
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
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 9184
telemt_me_refill_failed_total 684
telemt_me_writer_restored_same_endpoint_total 8423
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 746
telemt_user_connections_total{user="hello"} 67481
telemt_user_connections_current{user="hello"} 161
telemt_user_octets_from_client{user="hello"} 759658376 (724.47 MB)
telemt_user_octets_to_client{user="hello"} 18836928692 (17.54 GB)
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 31951.1 (8h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 96454
telemt_connections_bad_total 1489
telemt_handshake_timeouts_total 1999
telemt_upstream_connect_attempt_total 8866
telemt_upstream_connect_success_total 8866
telemt_upstream_connect_attempts_per_request{bucket="1"} 8866
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4297
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4559
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 169
telemt_me_reconnect_attempts_total 7250
telemt_me_reconnect_success_total 7185
telemt_me_reader_eof_total 7586
telemt_me_idle_close_by_peer_total 7586
telemt_me_route_drop_no_conn_total 35566
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 88995
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 28
telemt_desync_full_logged_total 14
telemt_desync_suppressed_total 14
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 7249
telemt_me_writer_restored_same_endpoint_total 7165
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 88969
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 2230475320 (2.08 GB)
telemt_user_octets_to_client{user="hello"} 44309020716 (41.27 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 31926.7 (8h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 132458
telemt_connections_bad_total 13063
telemt_handshake_timeouts_total 995
telemt_upstream_connect_attempt_total 7220
telemt_upstream_connect_success_total 7001
telemt_upstream_connect_fail_total 219
telemt_upstream_connect_attempts_per_request{bucket="1"} 7220
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3739
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 219
telemt_me_keepalive_timeout_total 313
telemt_me_reconnect_attempts_total 30701
telemt_me_reconnect_success_total 5367
telemt_me_reader_eof_total 6292
telemt_me_idle_close_by_peer_total 6292
telemt_me_route_drop_no_conn_total 47081
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 111596
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 392
telemt_desync_full_logged_total 118
telemt_desync_suppressed_total 274
telemt_desync_frames_bucket_total{bucket="1_2"} 117
telemt_desync_frames_bucket_total{bucket="3_10"} 145
telemt_desync_frames_bucket_total{bucket="gt_10"} 130
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 6220
telemt_me_refill_failed_total 790
telemt_me_writer_restored_same_endpoint_total 5359
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 853
telemt_user_connections_total{user="hello"} 111476
telemt_user_connections_current{user="hello"} 277
telemt_user_octets_from_client{user="hello"} 2105867740 (1.96 GB)
telemt_user_octets_to_client{user="hello"} 47592675580 (44.32 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 31896.2 (8h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75758
telemt_connections_bad_total 6701
telemt_handshake_timeouts_total 1091
telemt_upstream_connect_attempt_total 37598
telemt_upstream_connect_success_total 37204
telemt_upstream_connect_fail_total 394
telemt_upstream_connect_attempts_per_request{bucket="1"} 37598
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31531
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5638
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 394
telemt_me_keepalive_timeout_total 125
telemt_me_reconnect_attempts_total 43791
telemt_me_reconnect_success_total 3684
telemt_me_reader_eof_total 4934
telemt_me_idle_close_by_peer_total 4934
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 12778
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34342
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 448
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 323
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 372
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 4960
telemt_me_refill_failed_total 1256
telemt_me_writer_restored_same_endpoint_total 3667
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 1276
telemt_user_connections_total{user="hello"} 66226
telemt_user_connections_current{user="hello"} 115
telemt_user_octets_from_client{user="hello"} 596897412 (569.25 MB)
telemt_user_octets_to_client{user="hello"} 19717570336 (18.36 GB)
telemt_user_msgs_from_client{user="hello"} 509029
telemt_user_msgs_to_client{user="hello"} 1953797
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 31884.1 (8h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 200218
telemt_connections_bad_total 958
telemt_handshake_timeouts_total 1562
telemt_upstream_connect_attempt_total 6849
telemt_upstream_connect_success_total 6816
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 6849
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3187
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3619
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 366
telemt_me_reconnect_attempts_total 6250
telemt_me_reconnect_success_total 5182
telemt_me_reader_eof_total 5476
telemt_me_idle_close_by_peer_total 5475
telemt_me_route_drop_no_conn_total 77639
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 191339
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 253
telemt_desync_full_logged_total 100
telemt_desync_suppressed_total 153
telemt_desync_frames_bucket_total{bucket="1_2"} 66
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 5284
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 5175
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 191291
telemt_user_connections_current{user="hello"} 465
telemt_user_octets_from_client{user="hello"} 3598040848 (3.35 GB)
telemt_user_octets_to_client{user="hello"} 83941453312 (78.18 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 73
```