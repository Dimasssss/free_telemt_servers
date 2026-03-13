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

# Server Metrics 2026-03-13 20:15:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 132154.7 (36h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 558407
telemt_connections_bad_total 14807
telemt_handshake_timeouts_total 12581
telemt_upstream_connect_attempt_total 33509
telemt_upstream_connect_success_total 33338
telemt_upstream_connect_fail_total 171
telemt_upstream_connect_attempts_per_request{bucket="1"} 33509
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15330
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17863
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 171
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5051
telemt_me_reconnect_attempts_total 31009
telemt_me_reconnect_success_total 26357
telemt_me_reader_eof_total 28126
telemt_me_idle_close_by_peer_total 28125
telemt_me_route_drop_no_conn_total 184620
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 481411
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1535
telemt_desync_full_logged_total 523
telemt_desync_suppressed_total 1012
telemt_desync_frames_bucket_total{bucket="1_2"} 333
telemt_desync_frames_bucket_total{bucket="3_10"} 564
telemt_desync_frames_bucket_total{bucket="gt_10"} 638
telemt_pool_swap_total 117
telemt_me_writer_removed_unexpected_total 26797
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 26341
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 440
telemt_user_connections_total{user="hello"} 481306
telemt_user_connections_current{user="hello"} 312
telemt_user_octets_from_client{user="hello"} 8899190718 (8.29 GB)
telemt_user_octets_to_client{user="hello"} 232586321260 (216.61 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 132047.6 (36h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 281506
telemt_connections_bad_total 2099
telemt_handshake_timeouts_total 1881
telemt_upstream_connect_attempt_total 131997
telemt_upstream_connect_success_total 131033
telemt_upstream_connect_fail_total 964
telemt_upstream_connect_attempts_per_request{bucket="1"} 131997
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 100107
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28571
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2355
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 964
telemt_me_keepalive_timeout_total 3633
telemt_me_reconnect_attempts_total 139373
telemt_me_reconnect_success_total 26399
telemt_me_reader_eof_total 30663
telemt_me_idle_close_by_peer_total 30663
telemt_me_route_drop_no_conn_total 83857
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 169102
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 33
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
telemt_me_writer_removed_unexpected_total 30174
telemt_me_refill_failed_total 3525
telemt_me_writer_restored_same_endpoint_total 26382
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3775
telemt_user_connections_total{user="hello"} 266943
telemt_user_connections_current{user="hello"} 165
telemt_user_octets_from_client{user="hello"} 2771459229 (2.58 GB)
telemt_user_octets_to_client{user="hello"} 80083262128 (74.58 GB)
telemt_user_msgs_from_client{user="hello"} 1582304
telemt_user_msgs_to_client{user="hello"} 8601345
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 132011.8 (36h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 327867
telemt_connections_bad_total 2637
telemt_handshake_timeouts_total 23573
telemt_upstream_connect_attempt_total 34963
telemt_upstream_connect_success_total 34958
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 34963
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16172
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18745
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2803
telemt_me_reconnect_attempts_total 29571
telemt_me_reconnect_success_total 28333
telemt_me_reader_eof_total 30402
telemt_me_idle_close_by_peer_total 30402
telemt_me_route_drop_no_conn_total 117395
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 290222
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 122
telemt_me_writer_removed_unexpected_total 28655
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 28313
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 322
telemt_user_connections_total{user="hello"} 290133
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 11835612984 (11.02 GB)
telemt_user_octets_to_client{user="hello"} 121323334192 (112.99 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 131986.9 (36h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 433502
telemt_connections_bad_total 15232
telemt_handshake_timeouts_total 4167
telemt_upstream_connect_attempt_total 63160
telemt_upstream_connect_success_total 52853
telemt_upstream_connect_fail_total 10307
telemt_upstream_connect_attempts_per_request{bucket="1"} 63160
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32999
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19548
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 297
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10307
telemt_me_keepalive_timeout_total 4757
telemt_me_reconnect_attempts_total 120359
telemt_me_reconnect_success_total 27239
telemt_me_reader_eof_total 30920
telemt_me_idle_close_by_peer_total 30913
telemt_me_route_drop_no_conn_total 150375
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 364563
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1486
telemt_desync_full_logged_total 442
telemt_desync_suppressed_total 1044
telemt_desync_frames_bucket_total{bucket="1_2"} 357
telemt_desync_frames_bucket_total{bucket="3_10"} 563
telemt_desync_frames_bucket_total{bucket="gt_10"} 566
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 30491
telemt_me_refill_failed_total 2904
telemt_me_writer_restored_same_endpoint_total 27229
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3252
telemt_user_connections_total{user="hello"} 383426
telemt_user_connections_current{user="hello"} 180
telemt_user_octets_from_client{user="hello"} 8688101147 (8.09 GB)
telemt_user_octets_to_client{user="hello"} 139428874532 (129.85 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 82158.4 (22h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 140281
telemt_connections_bad_total 18439
telemt_handshake_timeouts_total 1439
telemt_upstream_connect_attempt_total 31350
telemt_upstream_connect_success_total 31049
telemt_upstream_connect_fail_total 301
telemt_upstream_connect_attempts_per_request{bucket="1"} 31350
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16005
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14940
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 301
telemt_me_keepalive_timeout_total 1264
telemt_me_reconnect_attempts_total 35425
telemt_me_reconnect_success_total 22033
telemt_me_reader_eof_total 23608
telemt_me_idle_close_by_peer_total 23608
telemt_me_route_drop_no_conn_total 43580
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 111033
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 604
telemt_desync_full_logged_total 140
telemt_desync_suppressed_total 464
telemt_desync_frames_bucket_total{bucket="1_2"} 85
telemt_desync_frames_bucket_total{bucket="3_10"} 302
telemt_desync_frames_bucket_total{bucket="gt_10"} 217
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 22657
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 22015
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 624
telemt_user_connections_total{user="hello"} 115927
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 1361518625 (1.27 GB)
telemt_user_octets_to_client{user="hello"} 51738766915 (48.19 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 131943.0 (36h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 808004
telemt_connections_bad_total 24869
telemt_handshake_timeouts_total 24924
telemt_upstream_connect_attempt_total 27231
telemt_upstream_connect_success_total 27087
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 27231
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12655
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14396
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_keepalive_timeout_total 3091
telemt_me_reconnect_attempts_total 25190
telemt_me_reconnect_success_total 20543
telemt_me_reader_eof_total 22033
telemt_me_idle_close_by_peer_total 22030
telemt_me_route_drop_no_conn_total 384386
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 757805
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 691
telemt_desync_full_logged_total 225
telemt_desync_suppressed_total 466
telemt_desync_frames_bucket_total{bucket="1_2"} 247
telemt_desync_frames_bucket_total{bucket="3_10"} 226
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 122
telemt_me_writer_removed_unexpected_total 20962
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 20536
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 419
telemt_user_connections_total{user="hello"} 730663
telemt_user_connections_current{user="hello"} 436
telemt_user_octets_from_client{user="hello"} 12713105624 (11.84 GB)
telemt_user_octets_to_client{user="hello"} 358315818728 (333.71 GB)
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 51
```