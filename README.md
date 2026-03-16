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

# Server Metrics 2026-03-16 10:06:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 129149.1 (35h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 633891
telemt_connections_bad_total 11255
telemt_handshake_timeouts_total 22360
telemt_upstream_connect_attempt_total 30293
telemt_upstream_connect_success_total 30148
telemt_upstream_connect_fail_total 145
telemt_upstream_connect_attempts_per_request{bucket="1"} 30293
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13434
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16667
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 145
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 32505
telemt_me_reconnect_success_total 23741
telemt_me_reader_eof_total 25487
telemt_me_idle_close_by_peer_total 25487
telemt_me_route_drop_no_conn_total 588067
telemt_me_route_drop_channel_closed_total 88
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 622176
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2935
telemt_desync_full_logged_total 1129
telemt_desync_suppressed_total 1806
telemt_desync_frames_bucket_total{bucket="1_2"} 644
telemt_desync_frames_bucket_total{bucket="3_10"} 1124
telemt_desync_frames_bucket_total{bucket="gt_10"} 1167
telemt_pool_swap_total 121
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 24271
telemt_me_refill_failed_total 270
telemt_me_writer_restored_same_endpoint_total 23707
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 530
telemt_user_connections_total{user="hello"} 558735
telemt_user_connections_current{user="hello"} 498
telemt_user_octets_from_client{user="hello"} 10931363960 (10.18 GB)
telemt_user_octets_to_client{user="hello"} 343392993708 (319.81 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 129155.4 (35h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 262022
telemt_connections_bad_total 3794
telemt_handshake_timeouts_total 15632
telemt_upstream_connect_attempt_total 34576
telemt_upstream_connect_success_total 34501
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 34576
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14894
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18905
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 702
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 37999
telemt_me_reconnect_success_total 27677
telemt_me_reader_eof_total 29691
telemt_me_idle_close_by_peer_total 29690
telemt_me_route_drop_no_conn_total 124751
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 233608
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
telemt_me_writer_removed_unexpected_total 28387
telemt_me_refill_failed_total 314
telemt_me_writer_restored_same_endpoint_total 27661
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 710
telemt_user_connections_total{user="hello"} 233143
telemt_user_connections_current{user="hello"} 287
telemt_user_octets_from_client{user="hello"} 5031096485 (4.69 GB)
telemt_user_octets_to_client{user="hello"} 125267821884 (116.66 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 129148.5 (35h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 268896
telemt_connections_bad_total 5767
telemt_handshake_timeouts_total 6276
telemt_upstream_connect_attempt_total 36032
telemt_upstream_connect_success_total 36024
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 36032
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15563
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20407
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 36961
telemt_me_reconnect_success_total 29538
telemt_me_reader_eof_total 31750
telemt_me_idle_close_by_peer_total 31749
telemt_me_route_drop_no_conn_total 92594
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 218123
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
telemt_me_writer_removed_unexpected_total 30060
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 29530
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 522
telemt_user_connections_total{user="hello"} 217820
telemt_user_connections_current{user="hello"} 259
telemt_user_octets_from_client{user="hello"} 17714340201 (16.50 GB)
telemt_user_octets_to_client{user="hello"} 120437541272 (112.17 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 129147.6 (35h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 389668
telemt_connections_bad_total 1402
telemt_handshake_timeouts_total 3503
telemt_upstream_connect_attempt_total 29870
telemt_upstream_connect_success_total 29830
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 29870
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14342
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15321
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 27047
telemt_me_reconnect_success_total 23402
telemt_me_reader_eof_total 25059
telemt_me_idle_close_by_peer_total 25058
telemt_me_route_drop_no_conn_total 135718
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 360743
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1302
telemt_desync_full_logged_total 449
telemt_desync_suppressed_total 853
telemt_desync_frames_bucket_total{bucket="1_2"} 261
telemt_desync_frames_bucket_total{bucket="3_10"} 554
telemt_desync_frames_bucket_total{bucket="gt_10"} 487
telemt_pool_swap_total 120
telemt_me_writer_removed_unexpected_total 23827
telemt_me_refill_failed_total 109
telemt_me_writer_restored_same_endpoint_total 23391
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 425
telemt_user_connections_total{user="hello"} 360614
telemt_user_connections_current{user="hello"} 408
telemt_user_octets_from_client{user="hello"} 5993335214 (5.58 GB)
telemt_user_octets_to_client{user="hello"} 143591590876 (133.73 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 104219.1 (28h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 244954
telemt_connections_bad_total 39393
telemt_handshake_timeouts_total 4270
telemt_upstream_connect_attempt_total 29688
telemt_upstream_connect_success_total 29526
telemt_upstream_connect_fail_total 162
telemt_upstream_connect_attempts_per_request{bucket="1"} 29688
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13083
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16293
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 162
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 118694
telemt_me_reconnect_success_total 24187
telemt_me_reader_eof_total 25687
telemt_me_idle_close_by_peer_total 25687
telemt_me_route_drop_no_conn_total 76210
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 194340
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 649
telemt_desync_full_logged_total 150
telemt_desync_suppressed_total 499
telemt_desync_frames_bucket_total{bucket="1_2"} 97
telemt_desync_frames_bucket_total{bucket="3_10"} 261
telemt_desync_frames_bucket_total{bucket="gt_10"} 291
telemt_pool_swap_total 89
telemt_me_writer_removed_unexpected_total 24392
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 24083
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 205
telemt_user_connections_total{user="hello"} 193954
telemt_user_connections_current{user="hello"} 194
telemt_user_octets_from_client{user="hello"} 2523960797 (2.35 GB)
telemt_user_octets_to_client{user="hello"} 84665558511 (78.85 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 129147.2 (35h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 883823
telemt_connections_bad_total 72733
telemt_handshake_timeouts_total 10340
telemt_upstream_connect_attempt_total 27113
telemt_upstream_connect_success_total 26971
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 27113
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12808
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14121
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 23137
telemt_me_reconnect_success_total 20534
telemt_me_reader_eof_total 21935
telemt_me_idle_close_by_peer_total 21935
telemt_me_route_drop_no_conn_total 673302
telemt_me_route_drop_channel_closed_total 123
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 871463
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 392
telemt_desync_full_logged_total 111
telemt_desync_suppressed_total 281
telemt_desync_frames_bucket_total{bucket="1_2"} 173
telemt_desync_frames_bucket_total{bucket="3_10"} 116
telemt_desync_frames_bucket_total{bucket="gt_10"} 103
telemt_pool_swap_total 120
telemt_me_writer_removed_unexpected_total 20858
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 20507
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 324
telemt_user_connections_total{user="hello"} 730088
telemt_user_connections_current{user="hello"} 663
telemt_user_octets_from_client{user="hello"} 15542703704 (14.48 GB)
telemt_user_octets_to_client{user="hello"} 436660088076 (406.67 GB)
telemt_user_unique_ips_current{user="hello"} 250
telemt_user_unique_ips_recent_window{user="hello"} 109
```