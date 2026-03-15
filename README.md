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

# Server Metrics 2026-03-15 19:13:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 75548.3 (20h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 354793
telemt_connections_bad_total 4319
telemt_handshake_timeouts_total 12985
telemt_upstream_connect_attempt_total 18193
telemt_upstream_connect_success_total 18101
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 18193
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8012
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10051
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 17746
telemt_me_reconnect_success_total 14347
telemt_me_reader_eof_total 15286
telemt_me_idle_close_by_peer_total 15286
telemt_me_route_drop_no_conn_total 471559
telemt_me_route_drop_channel_closed_total 76
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 385077
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1926
telemt_desync_full_logged_total 756
telemt_desync_suppressed_total 1170
telemt_desync_frames_bucket_total{bucket="1_2"} 365
telemt_desync_frames_bucket_total{bucket="3_10"} 749
telemt_desync_frames_bucket_total{bucket="gt_10"} 812
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 14609
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 14313
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 262
telemt_user_connections_total{user="hello"} 324136
telemt_user_connections_current{user="hello"} 352
telemt_user_octets_from_client{user="hello"} 6887791408 (6.41 GB)
telemt_user_octets_to_client{user="hello"} 249935810152 (232.77 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 75554.9 (20h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 144157
telemt_connections_bad_total 2843
telemt_handshake_timeouts_total 12828
telemt_upstream_connect_attempt_total 20312
telemt_upstream_connect_success_total 20304
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 20312
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8638
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11270
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 396
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 491
telemt_me_reconnect_attempts_total 18885
telemt_me_reconnect_success_total 16493
telemt_me_reader_eof_total 17622
telemt_me_idle_close_by_peer_total 17621
telemt_me_route_drop_no_conn_total 60615
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 122716
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3
telemt_desync_full_logged_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 16800
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 16477
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 307
telemt_user_connections_total{user="hello"} 122696
telemt_user_connections_current{user="hello"} 232
telemt_user_octets_from_client{user="hello"} 2343020532 (2.18 GB)
telemt_user_octets_to_client{user="hello"} 60750116724 (56.58 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 75547.4 (20h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 146759
telemt_connections_bad_total 1706
telemt_handshake_timeouts_total 3345
telemt_upstream_connect_attempt_total 21859
telemt_upstream_connect_success_total 21851
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 21859
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9504
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12305
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 25403
telemt_me_reconnect_success_total 18039
telemt_me_reader_eof_total 19368
telemt_me_idle_close_by_peer_total 19368
telemt_me_route_drop_no_conn_total 57452
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 129554
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 60
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 18449
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 18031
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 410
telemt_user_connections_total{user="hello"} 129445
telemt_user_connections_current{user="hello"} 163
telemt_user_octets_from_client{user="hello"} 10806770204 (10.06 GB)
telemt_user_octets_to_client{user="hello"} 70320542676 (65.49 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 75546.9 (20h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 206613
telemt_connections_bad_total 1115
telemt_handshake_timeouts_total 1460
telemt_upstream_connect_attempt_total 17749
telemt_upstream_connect_success_total 17735
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 17749
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8500
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9164
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 14069
telemt_me_reconnect_success_total 13984
telemt_me_reader_eof_total 14885
telemt_me_idle_close_by_peer_total 14885
telemt_me_route_drop_no_conn_total 76821
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 190419
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 686
telemt_desync_full_logged_total 256
telemt_desync_suppressed_total 430
telemt_desync_frames_bucket_total{bucket="1_2"} 139
telemt_desync_frames_bucket_total{bucket="3_10"} 317
telemt_desync_frames_bucket_total{bucket="gt_10"} 230
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 14150
telemt_me_writer_restored_same_endpoint_total 13973
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 166
telemt_user_connections_total{user="hello"} 190337
telemt_user_connections_current{user="hello"} 271
telemt_user_octets_from_client{user="hello"} 3602239228 (3.35 GB)
telemt_user_octets_to_client{user="hello"} 87719657192 (81.70 GB)
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 50618.4 (14h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 124232
telemt_connections_bad_total 25046
telemt_handshake_timeouts_total 2473
telemt_upstream_connect_attempt_total 14988
telemt_upstream_connect_success_total 14897
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 14988
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6794
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8019
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 106619
telemt_me_reconnect_success_total 12171
telemt_me_reader_eof_total 12791
telemt_me_idle_close_by_peer_total 12791
telemt_me_route_drop_no_conn_total 42890
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 93278
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 284
telemt_desync_full_logged_total 61
telemt_desync_suppressed_total 223
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 132
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 12250
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 12067
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 93408
telemt_user_connections_current{user="hello"} 77
telemt_user_octets_from_client{user="hello"} 1538934657 (1.43 GB)
telemt_user_octets_to_client{user="hello"} 35638486667 (33.19 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 75546.4 (20h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 510347
telemt_connections_bad_total 58007
telemt_handshake_timeouts_total 4202
telemt_upstream_connect_attempt_total 16133
telemt_upstream_connect_success_total 16041
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 16133
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7711
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8295
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 13568
telemt_me_reconnect_success_total 12261
telemt_me_reader_eof_total 13026
telemt_me_idle_close_by_peer_total 13026
telemt_me_route_drop_no_conn_total 326763
telemt_me_route_drop_channel_closed_total 88
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 471571
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 322
telemt_desync_full_logged_total 89
telemt_desync_suppressed_total 233
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 12431
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 12234
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 170
telemt_user_connections_total{user="hello"} 429340
telemt_user_connections_current{user="hello"} 532
telemt_user_octets_from_client{user="hello"} 10957052776 (10.20 GB)
telemt_user_octets_to_client{user="hello"} 235792681832 (219.60 GB)
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 66
```