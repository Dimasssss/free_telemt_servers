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

# Server Metrics 2026-03-13 06:06:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 81182.1 (22h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 307558
telemt_connections_bad_total 3086
telemt_handshake_timeouts_total 6305
telemt_upstream_connect_attempt_total 20495
telemt_upstream_connect_success_total 20398
telemt_upstream_connect_fail_total 97
telemt_upstream_connect_attempts_per_request{bucket="1"} 20495
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9189
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11161
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 97
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1612
telemt_me_reconnect_attempts_total 19803
telemt_me_reconnect_success_total 16303
telemt_me_reader_eof_total 17434
telemt_me_idle_close_by_peer_total 17433
telemt_me_route_drop_no_conn_total 95882
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 259645
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 904
telemt_desync_full_logged_total 336
telemt_desync_suppressed_total 568
telemt_desync_frames_bucket_total{bucket="1_2"} 178
telemt_desync_frames_bucket_total{bucket="3_10"} 332
telemt_desync_frames_bucket_total{bucket="gt_10"} 394
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 16589
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 16287
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 286
telemt_user_connections_total{user="hello"} 259582
telemt_user_connections_current{user="hello"} 289
telemt_user_octets_from_client{user="hello"} 4439417788 (4.13 GB)
telemt_user_octets_to_client{user="hello"} 124931405996 (116.35 GB)
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 81074.5 (22h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 140343
telemt_connections_bad_total 803
telemt_handshake_timeouts_total 1050
telemt_upstream_connect_attempt_total 42731
telemt_upstream_connect_success_total 42177
telemt_upstream_connect_fail_total 553
telemt_upstream_connect_attempts_per_request{bucket="1"} 42730
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25013
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16655
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 509
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 553
telemt_me_keepalive_timeout_total 616
telemt_me_reconnect_attempts_total 69511
telemt_me_reconnect_success_total 21634
telemt_me_reader_eof_total 23782
telemt_me_idle_close_by_peer_total 23782
telemt_me_route_drop_no_conn_total 53207
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 116864
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 17
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
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 23297
telemt_me_refill_failed_total 1494
telemt_me_writer_restored_same_endpoint_total 21619
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1663
telemt_user_connections_total{user="hello"} 133361
telemt_user_connections_current{user="hello"} 139
telemt_user_octets_from_client{user="hello"} 1386809772 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 40921901727 (38.11 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 81037.9 (22h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 170461
telemt_connections_bad_total 1909
telemt_handshake_timeouts_total 2760
telemt_upstream_connect_attempt_total 22258
telemt_upstream_connect_success_total 22256
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 22258
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10243
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11990
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 495
telemt_me_reconnect_attempts_total 19341
telemt_me_reconnect_success_total 18171
telemt_me_reader_eof_total 19474
telemt_me_idle_close_by_peer_total 19474
telemt_me_route_drop_no_conn_total 66018
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 159449
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 62
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 18370
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 18151
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 199
telemt_user_connections_total{user="hello"} 159377
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 2938191488 (2.74 GB)
telemt_user_octets_to_client{user="hello"} 72400408976 (67.43 GB)
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 81013.7 (22h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 245916
telemt_connections_bad_total 13610
telemt_handshake_timeouts_total 1825
telemt_upstream_connect_attempt_total 34493
telemt_upstream_connect_success_total 24580
telemt_upstream_connect_fail_total 9913
telemt_upstream_connect_attempts_per_request{bucket="1"} 34493
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12362
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12037
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 173
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9913
telemt_me_keepalive_timeout_total 3339
telemt_me_reconnect_attempts_total 69225
telemt_me_reconnect_success_total 17691
telemt_me_reader_eof_total 19836
telemt_me_idle_close_by_peer_total 19829
telemt_me_route_drop_no_conn_total 89509
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 206750
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 593
telemt_desync_full_logged_total 172
telemt_desync_suppressed_total 421
telemt_desync_frames_bucket_total{bucket="1_2"} 146
telemt_desync_frames_bucket_total{bucket="3_10"} 226
telemt_desync_frames_bucket_total{bucket="gt_10"} 221
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 19529
telemt_me_refill_failed_total 1606
telemt_me_writer_restored_same_endpoint_total 17681
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1838
telemt_user_connections_total{user="hello"} 209490
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 3321355102 (3.09 GB)
telemt_user_octets_to_client{user="hello"} 81952286185 (76.32 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 31185.3 (8h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34608
telemt_connections_bad_total 6298
telemt_handshake_timeouts_total 141
telemt_upstream_connect_attempt_total 10736
telemt_upstream_connect_success_total 10633
telemt_upstream_connect_fail_total 103
telemt_upstream_connect_attempts_per_request{bucket="1"} 10736
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4617
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5978
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 103
telemt_me_keepalive_timeout_total 255
telemt_me_reconnect_attempts_total 10027
telemt_me_reconnect_success_total 9065
telemt_me_reader_eof_total 9636
telemt_me_idle_close_by_peer_total 9636
telemt_me_route_drop_no_conn_total 9471
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 27265
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 9177
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 9047
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 112
telemt_user_connections_total{user="hello"} 27265
telemt_user_connections_current{user="hello"} 73
telemt_user_octets_from_client{user="hello"} 208640864 (198.98 MB)
telemt_user_octets_to_client{user="hello"} 9696078208 (9.03 GB)
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 80970.1 (22h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 414858
telemt_connections_bad_total 8032
telemt_handshake_timeouts_total 3144
telemt_upstream_connect_attempt_total 17256
telemt_upstream_connect_success_total 17162
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 17256
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7984
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9153
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_timeout_total 1452
telemt_me_reconnect_attempts_total 16785
telemt_me_reconnect_success_total 13153
telemt_me_reader_eof_total 14121
telemt_me_idle_close_by_peer_total 14118
telemt_me_route_drop_no_conn_total 184355
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 402438
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 357
telemt_desync_full_logged_total 134
telemt_desync_suppressed_total 223
telemt_desync_frames_bucket_total{bucket="1_2"} 85
telemt_desync_frames_bucket_total{bucket="3_10"} 127
telemt_desync_frames_bucket_total{bucket="gt_10"} 145
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 13431
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 13146
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 278
telemt_user_connections_total{user="hello"} 390683
telemt_user_connections_current{user="hello"} 386
telemt_user_octets_from_client{user="hello"} 6408761460 (5.97 GB)
telemt_user_octets_to_client{user="hello"} 230932036052 (215.07 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 59
```