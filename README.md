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

# Server Metrics 2026-03-14 20:38:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 26528.2 (7h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 135279
telemt_connections_bad_total 16109
telemt_handshake_timeouts_total 1395
telemt_upstream_connect_attempt_total 5976
telemt_upstream_connect_success_total 5974
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 5976
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2846
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3045
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 214
telemt_me_reconnect_attempts_total 4642
telemt_me_reconnect_success_total 4606
telemt_me_reader_eof_total 4888
telemt_me_idle_close_by_peer_total 4888
telemt_me_route_drop_no_conn_total 48673
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 111698
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 498
telemt_desync_full_logged_total 178
telemt_desync_suppressed_total 320
telemt_desync_frames_bucket_total{bucket="1_2"} 119
telemt_desync_frames_bucket_total{bucket="3_10"} 179
telemt_desync_frames_bucket_total{bucket="gt_10"} 200
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 4686
telemt_me_writer_restored_same_endpoint_total 4588
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 111620
telemt_user_connections_current{user="hello"} 300
telemt_user_octets_from_client{user="hello"} 2395858464 (2.23 GB)
telemt_user_octets_to_client{user="hello"} 66503947156 (61.94 GB)
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 26526.5 (7h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55388
telemt_connections_bad_total 686
telemt_handshake_timeouts_total 963
telemt_upstream_connect_attempt_total 6891
telemt_upstream_connect_success_total 6846
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 6890
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2801
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 132
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 129
telemt_me_reconnect_attempts_total 8055
telemt_me_reconnect_success_total 5476
telemt_me_reader_eof_total 5821
telemt_me_idle_close_by_peer_total 5821
telemt_me_route_drop_no_conn_total 28782
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 51580
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 5633
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 5471
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 51568
telemt_user_connections_current{user="hello"} 190
telemt_user_octets_from_client{user="hello"} 1324859060 (1.23 GB)
telemt_user_octets_to_client{user="hello"} 22358070840 (20.82 GB)
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 26530.9 (7h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61957
telemt_connections_bad_total 391
telemt_handshake_timeouts_total 1888
telemt_upstream_connect_attempt_total 8794
telemt_upstream_connect_success_total 8704
telemt_upstream_connect_fail_total 90
telemt_upstream_connect_attempts_per_request{bucket="1"} 8794
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4078
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4616
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 90
telemt_me_keepalive_timeout_total 248
telemt_me_reconnect_attempts_total 104881
telemt_me_reconnect_success_total 7017
telemt_me_reader_eof_total 7497
telemt_me_idle_close_by_peer_total 7497
telemt_me_route_drop_no_conn_total 23586
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 56442
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 7295
telemt_me_refill_failed_total 3169
telemt_me_writer_restored_same_endpoint_total 6971
telemt_me_writer_restored_fallback_total 46
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 278
telemt_user_connections_total{user="hello"} 56507
telemt_user_connections_current{user="hello"} 92
telemt_user_octets_from_client{user="hello"} 3833732873 (3.57 GB)
telemt_user_octets_to_client{user="hello"} 40873070514 (38.07 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 26535.6 (7h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79194
telemt_connections_bad_total 206
telemt_handshake_timeouts_total 592
telemt_upstream_connect_attempt_total 6543
telemt_upstream_connect_success_total 6503
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 6543
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3047
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3428
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 190
telemt_me_reconnect_attempts_total 4996
telemt_me_reconnect_success_total 4970
telemt_me_reader_eof_total 5229
telemt_me_idle_close_by_peer_total 5229
telemt_me_route_drop_no_conn_total 34285
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 74976
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 609
telemt_desync_full_logged_total 154
telemt_desync_suppressed_total 455
telemt_desync_frames_bucket_total{bucket="1_2"} 106
telemt_desync_frames_bucket_total{bucket="3_10"} 258
telemt_desync_frames_bucket_total{bucket="gt_10"} 245
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 5025
telemt_me_writer_restored_same_endpoint_total 4968
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 75023
telemt_user_connections_current{user="hello"} 167
telemt_user_octets_from_client{user="hello"} 1216638208 (1.13 GB)
telemt_user_octets_to_client{user="hello"} 26069491910 (24.28 GB)
telemt_user_msgs_from_client{user="hello"} 473
telemt_user_msgs_to_client{user="hello"} 2783
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 26528.9 (7h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57883
telemt_connections_bad_total 5106
telemt_handshake_timeouts_total 3308
telemt_upstream_connect_attempt_total 6333
telemt_upstream_connect_success_total 6262
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 6333
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2814
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3408
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 153
telemt_me_reconnect_attempts_total 11424
telemt_me_reconnect_success_total 4888
telemt_me_reader_eof_total 5311
telemt_me_idle_close_by_peer_total 5311
telemt_me_route_drop_no_conn_total 19226
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 46732
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 262
telemt_desync_full_logged_total 39
telemt_desync_suppressed_total 223
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 92
telemt_desync_frames_bucket_total{bucket="gt_10"} 133
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 5137
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 4884
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 249
telemt_user_connections_total{user="hello"} 46719
telemt_user_connections_current{user="hello"} 88
telemt_user_octets_from_client{user="hello"} 1374905240 (1.28 GB)
telemt_user_octets_to_client{user="hello"} 28565809044 (26.60 GB)
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 26528.4 (7h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 200045
telemt_connections_bad_total 7295
telemt_handshake_timeouts_total 2650
telemt_upstream_connect_attempt_total 5189
telemt_upstream_connect_success_total 5094
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 5189
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2483
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2606
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_timeout_total 251
telemt_me_reconnect_attempts_total 8733
telemt_me_reconnect_success_total 3727
telemt_me_reader_eof_total 4046
telemt_me_idle_close_by_peer_total 4046
telemt_me_route_drop_no_conn_total 112192
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 184231
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 55
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 35
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 3928
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 3723
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 201
telemt_user_connections_total{user="hello"} 180718
telemt_user_connections_current{user="hello"} 417
telemt_user_octets_from_client{user="hello"} 3912357280 (3.64 GB)
telemt_user_octets_to_client{user="hello"} 93708217472 (87.27 GB)
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 46
```