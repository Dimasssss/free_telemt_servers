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

# Server Metrics 2026-03-16 10:01:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 128842.3 (35h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 630564
telemt_connections_bad_total 11190
telemt_handshake_timeouts_total 22274
telemt_upstream_connect_attempt_total 30250
telemt_upstream_connect_success_total 30105
telemt_upstream_connect_fail_total 145
telemt_upstream_connect_attempts_per_request{bucket="1"} 30250
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13412
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16646
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 145
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 31434
telemt_me_reconnect_success_total 23702
telemt_me_reader_eof_total 25416
telemt_me_idle_close_by_peer_total 25416
telemt_me_route_drop_no_conn_total 587216
telemt_me_route_drop_channel_closed_total 86
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 619133
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2930
telemt_desync_full_logged_total 1126
telemt_desync_suppressed_total 1804
telemt_desync_frames_bucket_total{bucket="1_2"} 642
telemt_desync_frames_bucket_total{bucket="3_10"} 1121
telemt_desync_frames_bucket_total{bucket="gt_10"} 1167
telemt_pool_swap_total 121
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 24200
telemt_me_refill_failed_total 238
telemt_me_writer_restored_same_endpoint_total 23668
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 498
telemt_user_connections_total{user="hello"} 555693
telemt_user_connections_current{user="hello"} 542
telemt_user_octets_from_client{user="hello"} 10872848220 (10.13 GB)
telemt_user_octets_to_client{user="hello"} 342519648316 (319.00 GB)
telemt_user_unique_ips_current{user="hello"} 168
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 128849.9 (35h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 260251
telemt_connections_bad_total 3749
telemt_handshake_timeouts_total 15571
telemt_upstream_connect_attempt_total 34523
telemt_upstream_connect_success_total 34448
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 34523
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14873
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18876
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 699
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 37946
telemt_me_reconnect_success_total 27626
telemt_me_reader_eof_total 29639
telemt_me_idle_close_by_peer_total 29638
telemt_me_route_drop_no_conn_total 123851
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 231972
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 196
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 133
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 71
telemt_desync_frames_bucket_total{bucket="gt_10"} 87
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 28334
telemt_me_refill_failed_total 314
telemt_me_writer_restored_same_endpoint_total 27610
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 708
telemt_user_connections_total{user="hello"} 231507
telemt_user_connections_current{user="hello"} 279
telemt_user_octets_from_client{user="hello"} 5003981621 (4.66 GB)
telemt_user_octets_to_client{user="hello"} 124954210260 (116.37 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 128842.6 (35h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 267472
telemt_connections_bad_total 5765
telemt_handshake_timeouts_total 6218
telemt_upstream_connect_attempt_total 35975
telemt_upstream_connect_success_total 35967
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 35975
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15536
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20377
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 36904
telemt_me_reconnect_success_total 29482
telemt_me_reader_eof_total 31677
telemt_me_idle_close_by_peer_total 31676
telemt_me_route_drop_no_conn_total 92112
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 216825
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 100
telemt_desync_full_logged_total 39
telemt_desync_suppressed_total 61
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 116
telemt_me_writer_removed_unexpected_total 30004
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 29474
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 522
telemt_user_connections_total{user="hello"} 216525
telemt_user_connections_current{user="hello"} 243
telemt_user_octets_from_client{user="hello"} 17708437513 (16.49 GB)
telemt_user_octets_to_client{user="hello"} 120047105316 (111.80 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 128842.1 (35h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 387085
telemt_connections_bad_total 1400
telemt_handshake_timeouts_total 3498
telemt_upstream_connect_attempt_total 29831
telemt_upstream_connect_success_total 29791
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 29831
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14323
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15302
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 26273
telemt_me_reconnect_success_total 23365
telemt_me_reader_eof_total 24997
telemt_me_idle_close_by_peer_total 24996
telemt_me_route_drop_no_conn_total 134632
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 358252
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1301
telemt_desync_full_logged_total 448
telemt_desync_suppressed_total 853
telemt_desync_frames_bucket_total{bucket="1_2"} 261
telemt_desync_frames_bucket_total{bucket="3_10"} 553
telemt_desync_frames_bucket_total{bucket="gt_10"} 487
telemt_pool_swap_total 120
telemt_me_writer_removed_unexpected_total 23765
telemt_me_refill_failed_total 86
telemt_me_writer_restored_same_endpoint_total 23354
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 400
telemt_user_connections_total{user="hello"} 358124
telemt_user_connections_current{user="hello"} 465
telemt_user_octets_from_client{user="hello"} 5972599510 (5.56 GB)
telemt_user_octets_to_client{user="hello"} 142949438888 (133.13 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 103913.4 (28h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 243077
telemt_connections_bad_total 38756
telemt_handshake_timeouts_total 4260
telemt_upstream_connect_attempt_total 29639
telemt_upstream_connect_success_total 29477
telemt_upstream_connect_fail_total 162
telemt_upstream_connect_attempts_per_request{bucket="1"} 29639
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13063
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16264
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 162
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 118645
telemt_me_reconnect_success_total 24138
telemt_me_reader_eof_total 25638
telemt_me_idle_close_by_peer_total 25638
telemt_me_route_drop_no_conn_total 75837
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 193138
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 640
telemt_desync_full_logged_total 146
telemt_desync_suppressed_total 494
telemt_desync_frames_bucket_total{bucket="1_2"} 97
telemt_desync_frames_bucket_total{bucket="3_10"} 257
telemt_desync_frames_bucket_total{bucket="gt_10"} 286
telemt_pool_swap_total 89
telemt_me_writer_removed_unexpected_total 24343
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 24034
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 205
telemt_user_connections_total{user="hello"} 192752
telemt_user_connections_current{user="hello"} 185
telemt_user_octets_from_client{user="hello"} 2505141209 (2.33 GB)
telemt_user_octets_to_client{user="hello"} 84009474875 (78.24 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 128841.7 (35h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 880241
telemt_connections_bad_total 72661
telemt_handshake_timeouts_total 10295
telemt_upstream_connect_attempt_total 27021
telemt_upstream_connect_success_total 26879
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 27021
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12758
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14079
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 23051
telemt_me_reconnect_success_total 20449
telemt_me_reader_eof_total 21851
telemt_me_idle_close_by_peer_total 21851
telemt_me_route_drop_no_conn_total 671535
telemt_me_route_drop_channel_closed_total 121
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 868062
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 376
telemt_desync_full_logged_total 108
telemt_desync_suppressed_total 268
telemt_desync_frames_bucket_total{bucket="1_2"} 173
telemt_desync_frames_bucket_total{bucket="3_10"} 110
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 120
telemt_me_writer_removed_unexpected_total 20773
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 20422
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 324
telemt_user_connections_total{user="hello"} 726694
telemt_user_connections_current{user="hello"} 703
telemt_user_octets_from_client{user="hello"} 15489123372 (14.43 GB)
telemt_user_octets_to_client{user="hello"} 435677687280 (405.76 GB)
telemt_user_unique_ips_current{user="hello"} 265
telemt_user_unique_ips_recent_window{user="hello"} 124
```