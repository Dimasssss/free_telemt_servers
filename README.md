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

# Server Metrics 2026-03-14 11:06:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 185615.3 (51h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 727532
telemt_connections_bad_total 34239
telemt_handshake_timeouts_total 13974
telemt_upstream_connect_attempt_total 47268
telemt_upstream_connect_success_total 47033
telemt_upstream_connect_fail_total 235
telemt_upstream_connect_attempts_per_request{bucket="1"} 47268
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21484
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25397
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 235
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 6103
telemt_me_reconnect_attempts_total 43152
telemt_me_reconnect_success_total 37390
telemt_me_reader_eof_total 39985
telemt_me_idle_close_by_peer_total 39984
telemt_me_route_drop_no_conn_total 240618
telemt_me_route_drop_channel_closed_total 38
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 623634
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2539
telemt_desync_full_logged_total 842
telemt_desync_suppressed_total 1697
telemt_desync_frames_bucket_total{bucket="1_2"} 537
telemt_desync_frames_bucket_total{bucket="3_10"} 947
telemt_desync_frames_bucket_total{bucket="gt_10"} 1055
telemt_pool_swap_total 169
telemt_me_writer_removed_unexpected_total 37967
telemt_me_refill_failed_total 173
telemt_me_writer_restored_same_endpoint_total 37370
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 577
telemt_user_connections_total{user="hello"} 623523
telemt_user_connections_current{user="hello"} 464
telemt_user_octets_from_client{user="hello"} 17561202590 (16.36 GB)
telemt_user_octets_to_client{user="hello"} 300003316068 (279.40 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 185510.5 (51h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 362582
telemt_connections_bad_total 2836
telemt_handshake_timeouts_total 3293
telemt_upstream_connect_attempt_total 155079
telemt_upstream_connect_success_total 153716
telemt_upstream_connect_fail_total 1362
telemt_upstream_connect_attempts_per_request{bucket="1"} 155078
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 111974
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39274
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2467
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1362
telemt_me_keepalive_timeout_total 5509
telemt_me_reconnect_attempts_total 190407
telemt_me_reconnect_success_total 41155
telemt_me_reader_eof_total 46895
telemt_me_idle_close_by_peer_total 46895
telemt_me_route_drop_no_conn_total 124972
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 239126
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 46
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 46213
telemt_me_refill_failed_total 4657
telemt_me_writer_restored_same_endpoint_total 41138
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 5058
telemt_user_connections_total{user="hello"} 342231
telemt_user_connections_current{user="hello"} 157
telemt_user_octets_from_client{user="hello"} 3493197323 (3.25 GB)
telemt_user_octets_to_client{user="hello"} 109161730655 (101.66 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 185472.9 (51h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 418788
telemt_connections_bad_total 3283
telemt_handshake_timeouts_total 35907
telemt_upstream_connect_attempt_total 49316
telemt_upstream_connect_success_total 49307
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 49316
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22592
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26644
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3927
telemt_me_reconnect_attempts_total 41324
telemt_me_reconnect_success_total 40015
telemt_me_reader_eof_total 42988
telemt_me_idle_close_by_peer_total 42988
telemt_me_route_drop_no_conn_total 152266
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 364718
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 138
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 75
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 173
telemt_me_writer_removed_unexpected_total 40494
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 39994
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 479
telemt_user_connections_total{user="hello"} 364441
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 14389234760 (13.40 GB)
telemt_user_octets_to_client{user="hello"} 160513680264 (149.49 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 185448.7 (51h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 530501
telemt_connections_bad_total 16724
telemt_handshake_timeouts_total 5266
telemt_upstream_connect_attempt_total 79803
telemt_upstream_connect_success_total 69115
telemt_upstream_connect_fail_total 10688
telemt_upstream_connect_attempts_per_request{bucket="1"} 79803
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40246
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28496
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 364
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10688
telemt_me_keepalive_timeout_total 5698
telemt_me_reconnect_attempts_total 154267
telemt_me_reconnect_success_total 40845
telemt_me_reader_eof_total 45690
telemt_me_idle_close_by_peer_total 45682
telemt_me_route_drop_no_conn_total 192170
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 454579
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2034
telemt_desync_full_logged_total 606
telemt_desync_suppressed_total 1428
telemt_desync_frames_bucket_total{bucket="1_2"} 480
telemt_desync_frames_bucket_total{bucket="3_10"} 778
telemt_desync_frames_bucket_total{bucket="gt_10"} 776
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 44855
telemt_me_refill_failed_total 3536
telemt_me_writer_restored_same_endpoint_total 40835
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 4010
telemt_user_connections_total{user="hello"} 473445
telemt_user_connections_current{user="hello"} 167
telemt_user_octets_from_client{user="hello"} 10090992991 (9.40 GB)
telemt_user_octets_to_client{user="hello"} 194357721108 (181.01 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 135620.2 (37h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 228151
telemt_connections_bad_total 35769
telemt_handshake_timeouts_total 2018
telemt_upstream_connect_attempt_total 47684
telemt_upstream_connect_success_total 47211
telemt_upstream_connect_fail_total 473
telemt_upstream_connect_attempts_per_request{bucket="1"} 47684
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23553
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23500
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 158
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 473
telemt_me_keepalive_timeout_total 2884
telemt_me_reconnect_attempts_total 51457
telemt_me_reconnect_success_total 35573
telemt_me_reader_eof_total 38061
telemt_me_idle_close_by_peer_total 38061
telemt_me_route_drop_no_conn_total 69161
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 179359
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 770
telemt_desync_full_logged_total 190
telemt_desync_suppressed_total 580
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 366
telemt_desync_frames_bucket_total{bucket="gt_10"} 277
telemt_pool_swap_total 101
telemt_me_writer_removed_unexpected_total 36399
telemt_me_refill_failed_total 492
telemt_me_writer_restored_same_endpoint_total 35555
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 826
telemt_user_connections_total{user="hello"} 184115
telemt_user_connections_current{user="hello"} 75
telemt_user_octets_from_client{user="hello"} 2708341337 (2.52 GB)
telemt_user_octets_to_client{user="hello"} 85165087375 (79.32 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 185405.0 (51h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1077790
telemt_connections_bad_total 37354
telemt_handshake_timeouts_total 27000
telemt_upstream_connect_attempt_total 38740
telemt_upstream_connect_success_total 38537
telemt_upstream_connect_fail_total 203
telemt_upstream_connect_attempts_per_request{bucket="1"} 38740
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18251
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20245
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 203
telemt_me_keepalive_timeout_total 4936
telemt_me_reconnect_attempts_total 34075
telemt_me_reconnect_success_total 29385
telemt_me_reader_eof_total 31506
telemt_me_idle_close_by_peer_total 31503
telemt_me_route_drop_no_conn_total 505116
telemt_me_route_drop_channel_closed_total 26
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 999384
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 809
telemt_desync_full_logged_total 268
telemt_desync_suppressed_total 541
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 269
telemt_desync_frames_bucket_total{bucket="gt_10"} 280
telemt_pool_swap_total 172
telemt_me_writer_removed_unexpected_total 29901
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 29378
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 516
telemt_user_connections_total{user="hello"} 971969
telemt_user_connections_current{user="hello"} 452
telemt_user_octets_from_client{user="hello"} 18165266484 (16.92 GB)
telemt_user_octets_to_client{user="hello"} 488665143752 (455.10 GB)
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 64
```