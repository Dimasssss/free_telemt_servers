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

# Server Metrics 2026-03-17 08:16:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 48669.2 (13h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 341229
telemt_connections_bad_total 3569
telemt_handshake_timeouts_total 9990
telemt_upstream_connect_attempt_total 10060
telemt_upstream_connect_success_total 10006
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 10060
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4593
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5407
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 7614
telemt_me_reconnect_success_total 7583
telemt_me_reader_eof_total 8055
telemt_me_idle_close_by_peer_total 8055
telemt_me_route_drop_no_conn_total 105064
telemt_me_route_drop_channel_closed_total 25
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 308741
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2411
telemt_desync_full_logged_total 678
telemt_desync_suppressed_total 1733
telemt_desync_frames_bucket_total{bucket="1_2"} 563
telemt_desync_frames_bucket_total{bucket="3_10"} 1151
telemt_desync_frames_bucket_total{bucket="gt_10"} 697
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 7664
telemt_me_writer_restored_same_endpoint_total 7562
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 308482
telemt_user_connections_current{user="hello"} 948
telemt_user_octets_from_client{user="hello"} 4266647288 (3.97 GB)
telemt_user_octets_to_client{user="hello"} 129395603684 (120.51 GB)
telemt_user_unique_ips_current{user="hello"} 310
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 48920.7 (13h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 190232
telemt_connections_bad_total 2351
telemt_handshake_timeouts_total 12011
telemt_upstream_connect_attempt_total 13330
telemt_upstream_connect_success_total 13155
telemt_upstream_connect_fail_total 175
telemt_upstream_connect_attempts_per_request{bucket="1"} 13330
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7427
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 175
telemt_me_reconnect_attempts_total 12996
telemt_me_reconnect_success_total 10723
telemt_me_reader_eof_total 11347
telemt_me_idle_close_by_peer_total 11347
telemt_me_route_drop_no_conn_total 69192
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 166251
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 425
telemt_desync_full_logged_total 155
telemt_desync_suppressed_total 270
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 183
telemt_desync_frames_bucket_total{bucket="gt_10"} 115
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 10896
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 10707
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 166267
telemt_user_connections_current{user="hello"} 524
telemt_user_octets_from_client{user="hello"} 2027223504 (1.89 GB)
telemt_user_octets_to_client{user="hello"} 65814212908 (61.29 GB)
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 48697.0 (13h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117785
telemt_connections_bad_total 7507
telemt_handshake_timeouts_total 5726
telemt_upstream_connect_attempt_total 12738
telemt_upstream_connect_success_total 12672
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 12738
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5605
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7005
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 10271
telemt_me_reconnect_success_total 10209
telemt_me_reader_eof_total 10918
telemt_me_idle_close_by_peer_total 10918
telemt_me_route_drop_no_conn_total 36651
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 95665
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 216
telemt_desync_full_logged_total 54
telemt_desync_suppressed_total 162
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 80
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 10339
telemt_me_writer_restored_same_endpoint_total 10198
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 130
telemt_user_connections_total{user="hello"} 95610
telemt_user_connections_current{user="hello"} 276
telemt_user_octets_from_client{user="hello"} 6546289452 (6.10 GB)
telemt_user_octets_to_client{user="hello"} 31015287968 (28.89 GB)
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 48756.1 (13h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 248110
telemt_connections_bad_total 6154
telemt_handshake_timeouts_total 10308
telemt_upstream_connect_attempt_total 11192
telemt_upstream_connect_success_total 11097
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 11192
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5246
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5782
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 9656
telemt_me_reconnect_success_total 8590
telemt_me_reader_eof_total 9149
telemt_me_idle_close_by_peer_total 9149
telemt_me_route_drop_no_conn_total 67805
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 195309
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 425
telemt_desync_full_logged_total 151
telemt_desync_suppressed_total 274
telemt_desync_frames_bucket_total{bucket="1_2"} 107
telemt_desync_frames_bucket_total{bucket="3_10"} 176
telemt_desync_frames_bucket_total{bucket="gt_10"} 142
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 8748
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 8582
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 195306
telemt_user_connections_current{user="hello"} 678
telemt_user_octets_from_client{user="hello"} 2080192958 (1.94 GB)
telemt_user_octets_to_client{user="hello"} 87140878421 (81.16 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 48728.0 (13h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 143339
telemt_connections_bad_total 39113
telemt_handshake_timeouts_total 2609
telemt_upstream_connect_attempt_total 15038
telemt_upstream_connect_success_total 14836
telemt_upstream_connect_fail_total 202
telemt_upstream_connect_attempts_per_request{bucket="1"} 15038
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6631
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8012
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 193
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 202
telemt_me_reconnect_attempts_total 16979
telemt_me_reconnect_success_total 12275
telemt_me_reader_eof_total 12967
telemt_me_idle_close_by_peer_total 12967
telemt_me_route_drop_no_conn_total 37833
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 97090
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 234
telemt_desync_full_logged_total 59
telemt_desync_suppressed_total 175
telemt_desync_frames_bucket_total{bucket="1_2"} 106
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 12570
telemt_me_refill_failed_total 145
telemt_me_writer_restored_same_endpoint_total 12267
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 295
telemt_user_connections_total{user="hello"} 97127
telemt_user_connections_current{user="hello"} 221
telemt_user_octets_from_client{user="hello"} 990096371 (944.23 MB)
telemt_user_octets_to_client{user="hello"} 45760659866 (42.62 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 48889.6 (13h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 345087
telemt_connections_bad_total 44816
telemt_handshake_timeouts_total 3372
telemt_upstream_connect_attempt_total 10112
telemt_upstream_connect_success_total 10057
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 10112
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4902
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5140
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 11487
telemt_me_reconnect_success_total 7611
telemt_me_reader_eof_total 8230
telemt_me_idle_close_by_peer_total 8230
telemt_me_route_drop_no_conn_total 249747
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 360531
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 431
telemt_desync_full_logged_total 174
telemt_desync_suppressed_total 257
telemt_desync_frames_bucket_total{bucket="1_2"} 137
telemt_desync_frames_bucket_total{bucket="3_10"} 159
telemt_desync_frames_bucket_total{bucket="gt_10"} 135
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 7841
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 7597
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 230
telemt_user_connections_total{user="hello"} 282451
telemt_user_connections_current{user="hello"} 755
telemt_user_octets_from_client{user="hello"} 3995136244 (3.72 GB)
telemt_user_octets_to_client{user="hello"} 168850059800 (157.25 GB)
telemt_user_unique_ips_current{user="hello"} 257
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 36895.5 (10h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2527
telemt_connections_bad_total 202
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 18137
telemt_upstream_connect_success_total 18136
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 18137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10232
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7896
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 16332
telemt_me_reconnect_success_total 16240
telemt_me_reader_eof_total 17766
telemt_me_idle_close_by_peer_total 17766
telemt_me_route_drop_no_conn_total 477
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2294
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 16382
telemt_me_writer_restored_same_endpoint_total 16240
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 142
telemt_user_connections_total{user="hello"} 2294
telemt_user_connections_current{user="hello"} 42
telemt_user_octets_from_client{user="hello"} 339351752 (323.63 MB)
telemt_user_octets_to_client{user="hello"} 17288392356 (16.10 GB)
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 6
```