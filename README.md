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

# Server Metrics 2026-03-15 18:48:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 74018.8 (20h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 348263
telemt_connections_bad_total 4220
telemt_handshake_timeouts_total 12317
telemt_upstream_connect_attempt_total 17914
telemt_upstream_connect_success_total 17823
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 17914
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7902
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9883
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 17513
telemt_me_reconnect_success_total 14114
telemt_me_reader_eof_total 15038
telemt_me_idle_close_by_peer_total 15038
telemt_me_route_drop_no_conn_total 468477
telemt_me_route_drop_channel_closed_total 76
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 379439
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1919
telemt_desync_full_logged_total 753
telemt_desync_suppressed_total 1166
telemt_desync_frames_bucket_total{bucket="1_2"} 363
telemt_desync_frames_bucket_total{bucket="3_10"} 745
telemt_desync_frames_bucket_total{bucket="gt_10"} 811
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 14373
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 14080
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 259
telemt_user_connections_total{user="hello"} 318502
telemt_user_connections_current{user="hello"} 354
telemt_user_octets_from_client{user="hello"} 6503246104 (6.06 GB)
telemt_user_octets_to_client{user="hello"} 246807046532 (229.86 GB)
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 74025.6 (20h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 140274
telemt_connections_bad_total 2839
telemt_handshake_timeouts_total 12614
telemt_upstream_connect_attempt_total 19949
telemt_upstream_connect_success_total 19949
telemt_upstream_connect_attempts_per_request{bucket="1"} 19949
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8496
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11104
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 349
telemt_me_keepalive_timeout_total 44
telemt_me_reconnect_attempts_total 18566
telemt_me_reconnect_success_total 16198
telemt_me_reader_eof_total 17323
telemt_me_idle_close_by_peer_total 17322
telemt_me_route_drop_no_conn_total 58301
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 119131
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
telemt_me_writer_removed_unexpected_total 16489
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 16182
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 291
telemt_user_connections_total{user="hello"} 119111
telemt_user_connections_current{user="hello"} 191
telemt_user_octets_from_client{user="hello"} 2288822048 (2.13 GB)
telemt_user_octets_to_client{user="hello"} 59661244588 (55.56 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 74017.9 (20h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 143683
telemt_connections_bad_total 1701
telemt_handshake_timeouts_total 3310
telemt_upstream_connect_attempt_total 21554
telemt_upstream_connect_success_total 21546
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 21554
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9367
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12143
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 25141
telemt_me_reconnect_success_total 17781
telemt_me_reader_eof_total 19091
telemt_me_idle_close_by_peer_total 19091
telemt_me_route_drop_no_conn_total 56029
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 126702
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
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 18181
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 17773
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 400
telemt_user_connections_total{user="hello"} 126594
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 10776535184 (10.04 GB)
telemt_user_octets_to_client{user="hello"} 69669293708 (64.88 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 74017.4 (20h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 200404
telemt_connections_bad_total 963
telemt_handshake_timeouts_total 1377
telemt_upstream_connect_attempt_total 17484
telemt_upstream_connect_success_total 17470
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 17484
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8371
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9029
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 13847
telemt_me_reconnect_success_total 13764
telemt_me_reader_eof_total 14655
telemt_me_idle_close_by_peer_total 14655
telemt_me_route_drop_no_conn_total 75111
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 184750
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 655
telemt_desync_full_logged_total 246
telemt_desync_suppressed_total 409
telemt_desync_frames_bucket_total{bucket="1_2"} 138
telemt_desync_frames_bucket_total{bucket="3_10"} 305
telemt_desync_frames_bucket_total{bucket="gt_10"} 212
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 13927
telemt_me_writer_restored_same_endpoint_total 13753
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 163
telemt_user_connections_total{user="hello"} 184661
telemt_user_connections_current{user="hello"} 247
telemt_user_octets_from_client{user="hello"} 3456779376 (3.22 GB)
telemt_user_octets_to_client{user="hello"} 85969142296 (80.07 GB)
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 49089.0 (13h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 120959
telemt_connections_bad_total 24772
telemt_handshake_timeouts_total 2471
telemt_upstream_connect_attempt_total 14503
telemt_upstream_connect_success_total 14418
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 14503
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6600
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7740
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 106226
telemt_me_reconnect_success_total 11778
telemt_me_reader_eof_total 12381
telemt_me_idle_close_by_peer_total 12381
telemt_me_route_drop_no_conn_total 41313
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 90358
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
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 11853
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 11674
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 90490
telemt_user_connections_current{user="hello"} 98
telemt_user_octets_from_client{user="hello"} 1509610025 (1.41 GB)
telemt_user_octets_to_client{user="hello"} 34919409995 (32.52 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 74016.9 (20h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 498962
telemt_connections_bad_total 57846
telemt_handshake_timeouts_total 4030
telemt_upstream_connect_attempt_total 15905
telemt_upstream_connect_success_total 15813
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 15905
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7623
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8156
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 13383
telemt_me_reconnect_success_total 12078
telemt_me_reader_eof_total 12836
telemt_me_idle_close_by_peer_total 12836
telemt_me_route_drop_no_conn_total 320827
telemt_me_route_drop_channel_closed_total 84
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 461040
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 317
telemt_desync_full_logged_total 86
telemt_desync_suppressed_total 231
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 12248
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 12051
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 170
telemt_user_connections_total{user="hello"} 418810
telemt_user_connections_current{user="hello"} 533
telemt_user_octets_from_client{user="hello"} 10720973928 (9.98 GB)
telemt_user_octets_to_client{user="hello"} 231552235148 (215.65 GB)
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 58
```