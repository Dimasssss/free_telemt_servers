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

# Server Metrics 2026-03-13 14:24:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 111057.1 (30h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 459209
telemt_connections_bad_total 3217
telemt_handshake_timeouts_total 8552
telemt_upstream_connect_attempt_total 27969
telemt_upstream_connect_success_total 27839
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 27969
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12572
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15204
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2428
telemt_me_reconnect_attempts_total 25802
telemt_me_reconnect_success_total 22272
telemt_me_reader_eof_total 23792
telemt_me_idle_close_by_peer_total 23791
telemt_me_route_drop_no_conn_total 148858
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 401850
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1339
telemt_desync_full_logged_total 474
telemt_desync_suppressed_total 865
telemt_desync_frames_bucket_total{bucket="1_2"} 289
telemt_desync_frames_bucket_total{bucket="3_10"} 486
telemt_desync_frames_bucket_total{bucket="gt_10"} 564
telemt_pool_swap_total 100
telemt_me_writer_removed_unexpected_total 22615
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 22256
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 343
telemt_user_connections_total{user="hello"} 401428
telemt_user_connections_current{user="hello"} 398
telemt_user_octets_from_client{user="hello"} 7240551352 (6.74 GB)
telemt_user_octets_to_client{user="hello"} 185617588588 (172.87 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 110949.9 (30h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 217101
telemt_connections_bad_total 1785
telemt_handshake_timeouts_total 1541
telemt_upstream_connect_attempt_total 75776
telemt_upstream_connect_success_total 75029
telemt_upstream_connect_fail_total 747
telemt_upstream_connect_attempts_per_request{bucket="1"} 75776
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51565
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22741
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 723
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 747
telemt_me_keepalive_timeout_total 1396
telemt_me_reconnect_attempts_total 108050
telemt_me_reconnect_success_total 26022
telemt_me_reader_eof_total 29345
telemt_me_idle_close_by_peer_total 29345
telemt_me_route_drop_no_conn_total 80073
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 161921
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
telemt_me_writer_removed_unexpected_total 28809
telemt_me_refill_failed_total 2559
telemt_me_writer_restored_same_endpoint_total 26005
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2787
telemt_user_connections_total{user="hello"} 205154
telemt_user_connections_current{user="hello"} 199
telemt_user_octets_from_client{user="hello"} 2062805866 (1.92 GB)
telemt_user_octets_to_client{user="hello"} 65911845369 (61.39 GB)
telemt_user_msgs_from_client{user="hello"} 637138
telemt_user_msgs_to_client{user="hello"} 4378038
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 110913.7 (30h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 263159
telemt_connections_bad_total 2186
telemt_handshake_timeouts_total 11106
telemt_upstream_connect_attempt_total 29813
telemt_upstream_connect_success_total 29809
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 29813
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13836
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15945
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2284
telemt_me_reconnect_attempts_total 25419
telemt_me_reconnect_success_total 24203
telemt_me_reader_eof_total 25927
telemt_me_idle_close_by_peer_total 25927
telemt_me_route_drop_no_conn_total 95532
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 240435
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
telemt_pool_swap_total 100
telemt_me_writer_removed_unexpected_total 24468
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 24183
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 265
telemt_user_connections_total{user="hello"} 240349
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 9499473492 (8.85 GB)
telemt_user_octets_to_client{user="hello"} 101942496516 (94.94 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 110889.1 (30h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 361811
telemt_connections_bad_total 15043
telemt_handshake_timeouts_total 3616
telemt_upstream_connect_attempt_total 41790
telemt_upstream_connect_success_total 31658
telemt_upstream_connect_fail_total 10132
telemt_upstream_connect_attempts_per_request{bucket="1"} 41790
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15998
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15441
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10132
telemt_me_keepalive_timeout_total 4137
telemt_me_reconnect_attempts_total 96877
telemt_me_reconnect_success_total 23048
telemt_me_reader_eof_total 26053
telemt_me_idle_close_by_peer_total 26046
telemt_me_route_drop_no_conn_total 129675
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 312380
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1191
telemt_desync_full_logged_total 354
telemt_desync_suppressed_total 837
telemt_desync_frames_bucket_total{bucket="1_2"} 299
telemt_desync_frames_bucket_total{bucket="3_10"} 445
telemt_desync_frames_bucket_total{bucket="gt_10"} 447
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 25651
telemt_me_refill_failed_total 2302
telemt_me_writer_restored_same_endpoint_total 23038
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2603
telemt_user_connections_total{user="hello"} 315290
telemt_user_connections_current{user="hello"} 218
telemt_user_octets_from_client{user="hello"} 6812967578 (6.35 GB)
telemt_user_octets_to_client{user="hello"} 118734629185 (110.58 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 61060.8 (16h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93305
telemt_connections_bad_total 12293
telemt_handshake_timeouts_total 1208
telemt_upstream_connect_attempt_total 25266
telemt_upstream_connect_success_total 25061
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 25266
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13123
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11868
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_timeout_total 1027
telemt_me_reconnect_attempts_total 27025
telemt_me_reconnect_success_total 17104
telemt_me_reader_eof_total 18349
telemt_me_idle_close_by_peer_total 18349
telemt_me_route_drop_no_conn_total 27702
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 71927
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 273
telemt_desync_full_logged_total 54
telemt_desync_suppressed_total 219
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 133
telemt_desync_frames_bucket_total{bucket="gt_10"} 100
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 17561
telemt_me_refill_failed_total 308
telemt_me_writer_restored_same_endpoint_total 17086
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 457
telemt_user_connections_total{user="hello"} 76827
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 912312489 (870.05 MB)
telemt_user_octets_to_client{user="hello"} 22350840623 (20.82 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 110845.8 (30h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 652032
telemt_connections_bad_total 18005
telemt_handshake_timeouts_total 19789
telemt_upstream_connect_attempt_total 23338
telemt_upstream_connect_success_total 23220
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 23338
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10887
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12308
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 2529
telemt_me_reconnect_attempts_total 22316
telemt_me_reconnect_success_total 17691
telemt_me_reader_eof_total 18995
telemt_me_idle_close_by_peer_total 18992
telemt_me_route_drop_no_conn_total 314890
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 619504
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 475
telemt_desync_full_logged_total 178
telemt_desync_suppressed_total 297
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 177
telemt_desync_frames_bucket_total{bucket="gt_10"} 184
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 18064
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 17684
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 373
telemt_user_connections_total{user="hello"} 592451
telemt_user_connections_current{user="hello"} 425
telemt_user_octets_from_client{user="hello"} 10262192712 (9.56 GB)
telemt_user_octets_to_client{user="hello"} 310962644936 (289.61 GB)
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 64
```