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

# Server Metrics 2026-03-12 08:37:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 3866.2 (1h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21649
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 1937
telemt_upstream_connect_attempt_total 829
telemt_upstream_connect_success_total 827
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 829
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 385
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 441
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 37
telemt_me_reconnect_attempts_total 590
telemt_me_reconnect_success_total 587
telemt_me_reader_eof_total 585
telemt_me_idle_close_by_peer_total 585
telemt_me_route_drop_no_conn_total 5248
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18493
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 64
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 43
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 26
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 581
telemt_me_writer_restored_same_endpoint_total 571
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_user_connections_total{user="hello"} 18492
telemt_user_connections_current{user="hello"} 374
telemt_user_octets_from_client{user="hello"} 177848064 (169.61 MB)
telemt_user_octets_to_client{user="hello"} 6731306000 (6.27 GB)
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 3758.5 (1h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7777
telemt_connections_bad_total 10
telemt_handshake_timeouts_total 66
telemt_upstream_connect_attempt_total 1439
telemt_upstream_connect_success_total 1411
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 1439
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 434
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 977
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 3253
telemt_me_reconnect_success_total 1171
telemt_me_reader_eof_total 1198
telemt_me_idle_close_by_peer_total 1198
telemt_me_route_drop_no_conn_total 2632
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7395
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_me_writer_removed_unexpected_total 1221
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 1156
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 7392
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 52419120 (49.99 MB)
telemt_user_octets_to_client{user="hello"} 1545931388 (1.44 GB)
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 3722.2 (1h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12107
telemt_connections_bad_total 15
telemt_handshake_timeouts_total 95
telemt_upstream_connect_attempt_total 866
telemt_upstream_connect_success_total 866
telemt_upstream_connect_attempts_per_request{bucket="1"} 866
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 434
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 431
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 632
telemt_me_reconnect_success_total 630
telemt_me_reader_eof_total 622
telemt_me_idle_close_by_peer_total 622
telemt_me_route_drop_no_conn_total 3685
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11494
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 610
telemt_me_writer_restored_same_endpoint_total 610
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_user_connections_total{user="hello"} 11492
telemt_user_connections_current{user="hello"} 212
telemt_user_octets_from_client{user="hello"} 113829992 (108.56 MB)
telemt_user_octets_to_client{user="hello"} 13996517608 (13.04 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 3697.9 (1h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13841
telemt_connections_bad_total 1020
telemt_handshake_timeouts_total 52
telemt_upstream_connect_attempt_total 934
telemt_upstream_connect_success_total 890
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 933
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 377
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 512
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 682
telemt_me_reconnect_success_total 660
telemt_me_reader_eof_total 672
telemt_me_idle_close_by_peer_total 672
telemt_me_route_drop_no_conn_total 3672
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11821
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 671
telemt_me_writer_restored_same_endpoint_total 652
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 11823
telemt_user_connections_current{user="hello"} 254
telemt_user_octets_from_client{user="hello"} 534073348 (509.33 MB)
telemt_user_octets_to_client{user="hello"} 3391830264 (3.16 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 3667.2 (1h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7132
telemt_connections_bad_total 751
telemt_handshake_timeouts_total 89
telemt_upstream_connect_attempt_total 1295
telemt_upstream_connect_success_total 1249
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 1295
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 471
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 776
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 28
telemt_me_reconnect_attempts_total 2155
telemt_me_reconnect_success_total 1033
telemt_me_reader_eof_total 1042
telemt_me_idle_close_by_peer_total 1042
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 1842
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6126
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 80
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 91
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_me_writer_removed_unexpected_total 1065
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 1020
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 6124
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 18738636 (17.87 MB)
telemt_user_octets_to_client{user="hello"} 893870156 (852.46 MB)
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 3654.2 (1h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17452
telemt_connections_bad_total 518
telemt_handshake_timeouts_total 176
telemt_upstream_connect_attempt_total 611
telemt_upstream_connect_success_total 607
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 611
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 312
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 295
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 393
telemt_me_reconnect_success_total 392
telemt_me_reader_eof_total 390
telemt_me_idle_close_by_peer_total 390
telemt_me_route_drop_no_conn_total 7949
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16078
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 2
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 396
telemt_me_writer_restored_same_endpoint_total 385
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 16052
telemt_user_connections_current{user="hello"} 301
telemt_user_octets_from_client{user="hello"} 1269507944 (1.18 GB)
telemt_user_octets_to_client{user="hello"} 13616816952 (12.68 GB)
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 30
```