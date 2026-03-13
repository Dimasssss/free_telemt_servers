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

# Server Metrics 2026-03-13 13:02:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 106172.6 (29h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 435812
telemt_connections_bad_total 3212
telemt_handshake_timeouts_total 8423
telemt_upstream_connect_attempt_total 26888
telemt_upstream_connect_success_total 26761
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 26888
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12081
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14631
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2399
telemt_me_reconnect_attempts_total 24982
telemt_me_reconnect_success_total 21456
telemt_me_reader_eof_total 22905
telemt_me_idle_close_by_peer_total 22904
telemt_me_route_drop_no_conn_total 138510
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 379552
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1284
telemt_desync_full_logged_total 455
telemt_desync_suppressed_total 829
telemt_desync_frames_bucket_total{bucket="1_2"} 265
telemt_desync_frames_bucket_total{bucket="3_10"} 474
telemt_desync_frames_bucket_total{bucket="gt_10"} 545
telemt_pool_swap_total 94
telemt_me_writer_removed_unexpected_total 21789
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 21440
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 333
telemt_user_connections_total{user="hello"} 379140
telemt_user_connections_current{user="hello"} 416
telemt_user_octets_from_client{user="hello"} 6852930396 (6.38 GB)
telemt_user_octets_to_client{user="hello"} 164376436192 (153.09 GB)
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 106065.9 (29h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 201859
telemt_connections_bad_total 1678
telemt_handshake_timeouts_total 1492
telemt_upstream_connect_attempt_total 62938
telemt_upstream_connect_success_total 62225
telemt_upstream_connect_fail_total 713
telemt_upstream_connect_attempts_per_request{bucket="1"} 62938
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40410
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21213
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 602
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 713
telemt_me_keepalive_timeout_total 1370
telemt_me_reconnect_attempts_total 99747
telemt_me_reconnect_success_total 25977
telemt_me_reader_eof_total 29042
telemt_me_idle_close_by_peer_total 29042
telemt_me_route_drop_no_conn_total 79435
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 159761
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 24
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
telemt_me_writer_removed_unexpected_total 28506
telemt_me_refill_failed_total 2301
telemt_me_writer_restored_same_endpoint_total 25960
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2529
telemt_user_connections_total{user="hello"} 190498
telemt_user_connections_current{user="hello"} 234
telemt_user_octets_from_client{user="hello"} 1947003325 (1.81 GB)
telemt_user_octets_to_client{user="hello"} 62518097730 (58.22 GB)
telemt_user_msgs_from_client{user="hello"} 469975
telemt_user_msgs_to_client{user="hello"} 3310142
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 106029.3 (29h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 245913
telemt_connections_bad_total 2070
telemt_handshake_timeouts_total 8811
telemt_upstream_connect_attempt_total 28653
telemt_upstream_connect_success_total 28649
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 28653
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13275
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15347
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2211
telemt_me_reconnect_attempts_total 24519
telemt_me_reconnect_success_total 23306
telemt_me_reader_eof_total 24967
telemt_me_idle_close_by_peer_total 24967
telemt_me_route_drop_no_conn_total 90617
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 226106
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 92
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 95
telemt_me_writer_removed_unexpected_total 23561
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 23286
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 255
telemt_user_connections_total{user="hello"} 226021
telemt_user_connections_current{user="hello"} 209
telemt_user_octets_from_client{user="hello"} 9413151136 (8.77 GB)
telemt_user_octets_to_client{user="hello"} 98868794008 (92.08 GB)
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 106005.0 (29h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 342487
telemt_connections_bad_total 15024
telemt_handshake_timeouts_total 2727
telemt_upstream_connect_attempt_total 40462
telemt_upstream_connect_success_total 30370
telemt_upstream_connect_fail_total 10092
telemt_upstream_connect_attempts_per_request{bucket="1"} 40462
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15344
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14813
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 204
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10092
telemt_me_keepalive_timeout_total 4086
telemt_me_reconnect_attempts_total 93577
telemt_me_reconnect_success_total 22023
telemt_me_reader_eof_total 24927
telemt_me_idle_close_by_peer_total 24920
telemt_me_route_drop_no_conn_total 123154
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 295033
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1061
telemt_desync_full_logged_total 310
telemt_desync_suppressed_total 751
telemt_desync_frames_bucket_total{bucket="1_2"} 257
telemt_desync_frames_bucket_total{bucket="3_10"} 404
telemt_desync_frames_bucket_total{bucket="gt_10"} 400
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 24537
telemt_me_refill_failed_total 2231
telemt_me_writer_restored_same_endpoint_total 22013
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2514
telemt_user_connections_total{user="hello"} 297944
telemt_user_connections_current{user="hello"} 220
telemt_user_octets_from_client{user="hello"} 6026494330 (5.61 GB)
telemt_user_octets_to_client{user="hello"} 112275862021 (104.57 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 56176.5 (15h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82898
telemt_connections_bad_total 11115
telemt_handshake_timeouts_total 1190
telemt_upstream_connect_attempt_total 23959
telemt_upstream_connect_success_total 23767
telemt_upstream_connect_fail_total 192
telemt_upstream_connect_attempts_per_request{bucket="1"} 23959
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12585
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11117
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 192
telemt_me_keepalive_timeout_total 972
telemt_me_reconnect_attempts_total 25948
telemt_me_reconnect_success_total 16030
telemt_me_reader_eof_total 17208
telemt_me_idle_close_by_peer_total 17208
telemt_me_route_drop_no_conn_total 24597
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 63036
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 162
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 133
telemt_desync_frames_bucket_total{bucket="1_2"} 25
telemt_desync_frames_bucket_total{bucket="3_10"} 71
telemt_desync_frames_bucket_total{bucket="gt_10"} 66
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 16479
telemt_me_refill_failed_total 308
telemt_me_writer_restored_same_endpoint_total 16012
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 449
telemt_user_connections_total{user="hello"} 67945
telemt_user_connections_current{user="hello"} 124
telemt_user_octets_from_client{user="hello"} 596653881 (569.01 MB)
telemt_user_octets_to_client{user="hello"} 18964567051 (17.66 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 105961.7 (29h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 611246
telemt_connections_bad_total 17866
telemt_handshake_timeouts_total 16036
telemt_upstream_connect_attempt_total 22437
telemt_upstream_connect_success_total 22322
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 22437
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10473
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11824
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_keepalive_timeout_total 2503
telemt_me_reconnect_attempts_total 21676
telemt_me_reconnect_success_total 17053
telemt_me_reader_eof_total 18307
telemt_me_idle_close_by_peer_total 18304
telemt_me_route_drop_no_conn_total 299465
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 583572
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 471
telemt_desync_full_logged_total 176
telemt_desync_suppressed_total 295
telemt_desync_frames_bucket_total{bucket="1_2"} 110
telemt_desync_frames_bucket_total{bucket="3_10"} 177
telemt_desync_frames_bucket_total{bucket="gt_10"} 184
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 17418
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 17046
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 365
telemt_user_connections_total{user="hello"} 556620
telemt_user_connections_current{user="hello"} 469
telemt_user_octets_from_client{user="hello"} 9819748804 (9.15 GB)
telemt_user_octets_to_client{user="hello"} 294619493816 (274.39 GB)
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 65
```