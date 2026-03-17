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

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-17 05:43:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 39509.0 (10h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 221796
telemt_connections_bad_total 3244
telemt_handshake_timeouts_total 7357
telemt_upstream_connect_attempt_total 8311
telemt_upstream_connect_success_total 8268
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 8311
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3764
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4499
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6337
telemt_me_reconnect_success_total 6313
telemt_me_reader_eof_total 6718
telemt_me_idle_close_by_peer_total 6718
telemt_me_route_drop_no_conn_total 69074
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 199968
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1338
telemt_desync_full_logged_total 454
telemt_desync_suppressed_total 884
telemt_desync_frames_bucket_total{bucket="1_2"} 304
telemt_desync_frames_bucket_total{bucket="3_10"} 684
telemt_desync_frames_bucket_total{bucket="gt_10"} 350
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 6377
telemt_me_writer_restored_same_endpoint_total 6292
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 199763
telemt_user_connections_current{user="hello"} 606
telemt_user_octets_from_client{user="hello"} 2729354340 (2.54 GB)
telemt_user_octets_to_client{user="hello"} 89830664240 (83.66 GB)
telemt_user_unique_ips_current{user="hello"} 205
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 39760.2 (11h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128231
telemt_connections_bad_total 2196
telemt_handshake_timeouts_total 10242
telemt_upstream_connect_attempt_total 11018
telemt_upstream_connect_success_total 10874
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 11018
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4543
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6255
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_reconnect_attempts_total 10061
telemt_me_reconnect_success_total 8887
telemt_me_reader_eof_total 9395
telemt_me_idle_close_by_peer_total 9395
telemt_me_route_drop_no_conn_total 48969
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 111054
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 309
telemt_desync_full_logged_total 110
telemt_desync_suppressed_total 199
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 152
telemt_desync_frames_bucket_total{bucket="gt_10"} 83
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 9006
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 8871
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 119
telemt_user_connections_total{user="hello"} 111065
telemt_user_connections_current{user="hello"} 311
telemt_user_octets_from_client{user="hello"} 1409045228 (1.31 GB)
telemt_user_octets_to_client{user="hello"} 48286501064 (44.97 GB)
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 39536.7 (10h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76963
telemt_connections_bad_total 1107
telemt_handshake_timeouts_total 2586
telemt_upstream_connect_attempt_total 10652
telemt_upstream_connect_success_total 10597
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 10652
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4690
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5845
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 8671
telemt_me_reconnect_success_total 8625
telemt_me_reader_eof_total 9220
telemt_me_idle_close_by_peer_total 9220
telemt_me_route_drop_no_conn_total 25721
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 65900
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 46
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 8731
telemt_me_writer_restored_same_endpoint_total 8614
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 65884
telemt_user_connections_current{user="hello"} 190
telemt_user_octets_from_client{user="hello"} 5984500476 (5.57 GB)
telemt_user_octets_to_client{user="hello"} 21690448420 (20.20 GB)
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 39595.7 (10h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 130018
telemt_connections_bad_total 3723
telemt_handshake_timeouts_total 4217
telemt_upstream_connect_attempt_total 8938
telemt_upstream_connect_success_total 8862
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 8938
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4135
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4668
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_reconnect_attempts_total 6906
telemt_me_reconnect_success_total 6853
telemt_me_reader_eof_total 7299
telemt_me_idle_close_by_peer_total 7299
telemt_me_route_drop_no_conn_total 43652
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 118190
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 234
telemt_desync_full_logged_total 71
telemt_desync_suppressed_total 163
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 87
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 6954
telemt_me_writer_restored_same_endpoint_total 6846
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 101
telemt_user_connections_total{user="hello"} 118207
telemt_user_connections_current{user="hello"} 373
telemt_user_octets_from_client{user="hello"} 1298927730 (1.21 GB)
telemt_user_octets_to_client{user="hello"} 56881997677 (52.98 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 39567.6 (10h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99956
telemt_connections_bad_total 28346
telemt_handshake_timeouts_total 1961
telemt_upstream_connect_attempt_total 11797
telemt_upstream_connect_success_total 11642
telemt_upstream_connect_fail_total 155
telemt_upstream_connect_attempts_per_request{bucket="1"} 11797
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5214
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6250
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 178
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 155
telemt_me_reconnect_attempts_total 11836
telemt_me_reconnect_success_total 9575
telemt_me_reader_eof_total 10103
telemt_me_idle_close_by_peer_total 10103
telemt_me_route_drop_no_conn_total 26175
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 66989
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 38
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 9770
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 9567
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 195
telemt_user_connections_total{user="hello"} 67087
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 735499883 (701.43 MB)
telemt_user_octets_to_client{user="hello"} 28955722894 (26.97 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 39728.8 (11h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 239673
telemt_connections_bad_total 29639
telemt_handshake_timeouts_total 1909
telemt_upstream_connect_attempt_total 8148
telemt_upstream_connect_success_total 8104
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 8148
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3872
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4222
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 6137
telemt_me_reconnect_success_total 6109
telemt_me_reader_eof_total 6552
telemt_me_idle_close_by_peer_total 6552
telemt_me_route_drop_no_conn_total 202883
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 277321
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 239
telemt_desync_full_logged_total 121
telemt_desync_suppressed_total 118
telemt_desync_frames_bucket_total{bucket="1_2"} 81
telemt_desync_frames_bucket_total{bucket="3_10"} 83
telemt_desync_frames_bucket_total{bucket="gt_10"} 75
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 6199
telemt_me_writer_restored_same_endpoint_total 6099
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 199574
telemt_user_connections_current{user="hello"} 565
telemt_user_octets_from_client{user="hello"} 3083322676 (2.87 GB)
telemt_user_octets_to_client{user="hello"} 148034590412 (137.87 GB)
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 27735.2 (7h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 622
telemt_connections_bad_total 190
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 13744
telemt_upstream_connect_success_total 13744
telemt_upstream_connect_attempts_per_request{bucket="1"} 13744
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7904
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5833
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 12376
telemt_me_reconnect_success_total 12309
telemt_me_reader_eof_total 13517
telemt_me_idle_close_by_peer_total 13517
telemt_me_route_drop_no_conn_total 57
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 426
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 12423
telemt_me_writer_restored_same_endpoint_total 12309
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 114
telemt_user_connections_total{user="hello"} 426
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 169545592 (161.69 MB)
telemt_user_octets_to_client{user="hello"} 2564929588 (2.39 GB)
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```