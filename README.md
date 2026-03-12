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

# Server Metrics 2026-03-12 22:20:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 53248.3 (14h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 244077
telemt_connections_bad_total 2687
telemt_handshake_timeouts_total 5204
telemt_upstream_connect_attempt_total 13385
telemt_upstream_connect_success_total 13324
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 13385
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5875
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7404
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1468
telemt_me_reconnect_attempts_total 14069
telemt_me_reconnect_success_total 10601
telemt_me_reader_eof_total 11291
telemt_me_idle_close_by_peer_total 11290
telemt_me_route_drop_no_conn_total 75061
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 200788
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 679
telemt_desync_full_logged_total 251
telemt_desync_suppressed_total 428
telemt_desync_frames_bucket_total{bucket="1_2"} 123
telemt_desync_frames_bucket_total{bucket="3_10"} 255
telemt_desync_frames_bucket_total{bucket="gt_10"} 301
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 10830
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 10585
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 229
telemt_user_connections_total{user="hello"} 200555
telemt_user_connections_current{user="hello"} 245
telemt_user_octets_from_client{user="hello"} 3756751260 (3.50 GB)
telemt_user_octets_to_client{user="hello"} 97920265308 (91.20 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 53141.3 (14h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 109304
telemt_connections_bad_total 565
telemt_handshake_timeouts_total 814
telemt_upstream_connect_attempt_total 31467
telemt_upstream_connect_success_total 31121
telemt_upstream_connect_fail_total 346
telemt_upstream_connect_attempts_per_request{bucket="1"} 31467
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20746
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9876
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 499
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 346
telemt_me_keepalive_timeout_total 383
telemt_me_reconnect_attempts_total 52599
telemt_me_reconnect_success_total 11950
telemt_me_reader_eof_total 13490
telemt_me_idle_close_by_peer_total 13490
telemt_me_route_drop_no_conn_total 39894
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 87478
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 13
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
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 13308
telemt_me_refill_failed_total 1269
telemt_me_writer_restored_same_endpoint_total 11935
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1358
telemt_user_connections_total{user="hello"} 103979
telemt_user_connections_current{user="hello"} 87
telemt_user_octets_from_client{user="hello"} 1157703496 (1.08 GB)
telemt_user_octets_to_client{user="hello"} 33292201211 (31.01 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 53105.0 (14h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 135584
telemt_connections_bad_total 1581
telemt_handshake_timeouts_total 2217
telemt_upstream_connect_attempt_total 14601
telemt_upstream_connect_success_total 14600
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 14601
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6874
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7709
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 318
telemt_me_reconnect_attempts_total 13039
telemt_me_reconnect_success_total 11897
telemt_me_reader_eof_total 12675
telemt_me_idle_close_by_peer_total 12675
telemt_me_route_drop_no_conn_total 50944
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 126657
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 52
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 12045
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 11877
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 148
telemt_user_connections_total{user="hello"} 126624
telemt_user_connections_current{user="hello"} 60
telemt_user_octets_from_client{user="hello"} 2569890172 (2.39 GB)
telemt_user_octets_to_client{user="hello"} 59996998052 (55.88 GB)
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 53080.5 (14h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 197784
telemt_connections_bad_total 13239
telemt_handshake_timeouts_total 1370
telemt_upstream_connect_attempt_total 25796
telemt_upstream_connect_success_total 16111
telemt_upstream_connect_fail_total 9685
telemt_upstream_connect_attempts_per_request{bucket="1"} 25796
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8688
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7304
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9685
telemt_me_keepalive_timeout_total 2473
telemt_me_reconnect_attempts_total 42826
telemt_me_reconnect_success_total 10581
telemt_me_reader_eof_total 11960
telemt_me_idle_close_by_peer_total 11953
telemt_me_route_drop_no_conn_total 69258
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 161923
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 499
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 356
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 186
telemt_desync_frames_bucket_total{bucket="gt_10"} 189
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 11756
telemt_me_refill_failed_total 1004
telemt_me_writer_restored_same_endpoint_total 10571
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1175
telemt_user_connections_total{user="hello"} 164677
telemt_user_connections_current{user="hello"} 105
telemt_user_octets_from_client{user="hello"} 2962187310 (2.76 GB)
telemt_user_octets_to_client{user="hello"} 67386534841 (62.76 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 3252.2 (0h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3183
telemt_connections_bad_total 583
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 904
telemt_upstream_connect_success_total 897
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 904
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 432
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 459
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 700
telemt_me_reconnect_success_total 700
telemt_me_reader_eof_total 723
telemt_me_idle_close_by_peer_total 723
telemt_me_route_drop_no_conn_total 960
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2456
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 700
telemt_me_writer_restored_same_endpoint_total 684
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 25
telemt_user_connections_total{user="hello"} 2456
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 7246420 (6.91 MB)
telemt_user_octets_to_client{user="hello"} 1066060836 (1016.67 MB)
telemt_user_unique_ips_current{user="hello"} 14
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 53037.0 (14h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 320890
telemt_connections_bad_total 5067
telemt_handshake_timeouts_total 2480
telemt_upstream_connect_attempt_total 11047
telemt_upstream_connect_success_total 10986
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 11047
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5149
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5823
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_timeout_total 502
telemt_me_reconnect_attempts_total 11948
telemt_me_reconnect_success_total 8339
telemt_me_reader_eof_total 8907
telemt_me_idle_close_by_peer_total 8906
telemt_me_route_drop_no_conn_total 145723
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 315524
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 293
telemt_desync_full_logged_total 110
telemt_desync_suppressed_total 183
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 110
telemt_desync_frames_bucket_total{bucket="gt_10"} 109
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 8555
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 8332
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 216
telemt_user_connections_total{user="hello"} 303827
telemt_user_connections_current{user="hello"} 259
telemt_user_octets_from_client{user="hello"} 5382985792 (5.01 GB)
telemt_user_octets_to_client{user="hello"} 155562236716 (144.88 GB)
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 24
```