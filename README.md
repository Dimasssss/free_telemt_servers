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

# Server Metrics 2026-03-16 13:05:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 139888.8 (38h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 789842
telemt_connections_bad_total 54230
telemt_handshake_timeouts_total 25510
telemt_upstream_connect_attempt_total 32355
telemt_upstream_connect_success_total 32197
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 32355
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14384
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17766
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 39466
telemt_me_reconnect_success_total 25231
telemt_me_reader_eof_total 27197
telemt_me_idle_close_by_peer_total 27197
telemt_me_route_drop_no_conn_total 617298
telemt_me_route_drop_channel_closed_total 98
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 724314
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3451
telemt_desync_full_logged_total 1302
telemt_desync_suppressed_total 2149
telemt_desync_frames_bucket_total{bucket="1_2"} 729
telemt_desync_frames_bucket_total{bucket="3_10"} 1446
telemt_desync_frames_bucket_total{bucket="gt_10"} 1276
telemt_pool_swap_total 125
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 25950
telemt_me_refill_failed_total 440
telemt_me_writer_restored_same_endpoint_total 25196
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 719
telemt_user_connections_total{user="hello"} 660785
telemt_user_connections_current{user="hello"} 779
telemt_user_octets_from_client{user="hello"} 13756498140 (12.81 GB)
telemt_user_octets_to_client{user="hello"} 378022357388 (352.06 GB)
telemt_user_unique_ips_current{user="hello"} 232
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 139896.9 (38h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 332170
telemt_connections_bad_total 4716
telemt_handshake_timeouts_total 21193
telemt_upstream_connect_attempt_total 37399
telemt_upstream_connect_success_total 37292
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 37399
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16095
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20305
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 886
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_keepalive_timeout_total 1697
telemt_me_reconnect_attempts_total 44634
telemt_me_reconnect_success_total 29695
telemt_me_reader_eof_total 31904
telemt_me_idle_close_by_peer_total 31903
telemt_me_route_drop_no_conn_total 156266
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 294148
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 247
telemt_desync_full_logged_total 80
telemt_desync_suppressed_total 167
telemt_desync_frames_bucket_total{bucket="1_2"} 54
telemt_desync_frames_bucket_total{bucket="3_10"} 92
telemt_desync_frames_bucket_total{bucket="gt_10"} 101
telemt_pool_swap_total 113
telemt_me_writer_removed_unexpected_total 30589
telemt_me_refill_failed_total 457
telemt_me_writer_restored_same_endpoint_total 29679
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 894
telemt_user_connections_total{user="hello"} 293820
telemt_user_connections_current{user="hello"} 447
telemt_user_octets_from_client{user="hello"} 5837196309 (5.44 GB)
telemt_user_octets_to_client{user="hello"} 142054992824 (132.30 GB)
telemt_user_msgs_from_client{user="hello"} 994
telemt_user_msgs_to_client{user="hello"} 1709
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 139888.4 (38h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 317594
telemt_connections_bad_total 7695
telemt_handshake_timeouts_total 9024
telemt_upstream_connect_attempt_total 38580
telemt_upstream_connect_success_total 38572
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 38580
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16673
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21838
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 38978
telemt_me_reconnect_success_total 31529
telemt_me_reader_eof_total 33852
telemt_me_idle_close_by_peer_total 33851
telemt_me_route_drop_no_conn_total 107477
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 259265
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 119
telemt_desync_full_logged_total 46
telemt_desync_suppressed_total 73
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 123
telemt_me_writer_removed_unexpected_total 32085
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 31521
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 556
telemt_user_connections_total{user="hello"} 258859
telemt_user_connections_current{user="hello"} 361
telemt_user_octets_from_client{user="hello"} 19186588849 (17.87 GB)
telemt_user_octets_to_client{user="hello"} 132943084724 (123.81 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 139888.0 (38h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 488753
telemt_connections_bad_total 5602
telemt_handshake_timeouts_total 6415
telemt_upstream_connect_attempt_total 32505
telemt_upstream_connect_success_total 32456
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 32505
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15640
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16621
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 179
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 127
telemt_me_reconnect_attempts_total 31697
telemt_me_reconnect_success_total 25468
telemt_me_reader_eof_total 27275
telemt_me_idle_close_by_peer_total 27274
telemt_me_route_drop_no_conn_total 162562
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 445737
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1619
telemt_desync_full_logged_total 536
telemt_desync_suppressed_total 1083
telemt_desync_frames_bucket_total{bucket="1_2"} 328
telemt_desync_frames_bucket_total{bucket="3_10"} 698
telemt_desync_frames_bucket_total{bucket="gt_10"} 593
telemt_pool_swap_total 124
telemt_me_writer_removed_unexpected_total 26003
telemt_me_refill_failed_total 189
telemt_me_writer_restored_same_endpoint_total 25457
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 535
telemt_user_connections_total{user="hello"} 445554
telemt_user_connections_current{user="hello"} 545
telemt_user_octets_from_client{user="hello"} 6751044274 (6.29 GB)
telemt_user_octets_to_client{user="hello"} 167279881884 (155.79 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 114959.3 (31h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 300666
telemt_connections_bad_total 55058
telemt_handshake_timeouts_total 5434
telemt_upstream_connect_attempt_total 32633
telemt_upstream_connect_success_total 32454
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 32633
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14244
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18032
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 178
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_keepalive_timeout_total 52
telemt_me_reconnect_attempts_total 122180
telemt_me_reconnect_success_total 26559
telemt_me_reader_eof_total 28203
telemt_me_idle_close_by_peer_total 28203
telemt_me_route_drop_no_conn_total 89464
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 230906
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 721
telemt_desync_full_logged_total 175
telemt_desync_suppressed_total 546
telemt_desync_frames_bucket_total{bucket="1_2"} 107
telemt_desync_frames_bucket_total{bucket="3_10"} 293
telemt_desync_frames_bucket_total{bucket="gt_10"} 321
telemt_pool_swap_total 95
telemt_me_writer_removed_unexpected_total 26836
telemt_me_refill_failed_total 3067
telemt_me_writer_restored_same_endpoint_total 26455
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 277
telemt_user_connections_total{user="hello"} 230507
telemt_user_connections_current{user="hello"} 190
telemt_user_octets_from_client{user="hello"} 2980927517 (2.78 GB)
telemt_user_octets_to_client{user="hello"} 105387651343 (98.15 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 139887.4 (38h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1020817
telemt_connections_bad_total 78237
telemt_handshake_timeouts_total 13067
telemt_upstream_connect_attempt_total 29673
telemt_upstream_connect_success_total 29517
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 29673
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13871
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15595
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_keepalive_timeout_total 168
telemt_me_reconnect_attempts_total 26162
telemt_me_reconnect_success_total 22510
telemt_me_reader_eof_total 24031
telemt_me_idle_close_by_peer_total 24030
telemt_me_route_drop_no_conn_total 724616
telemt_me_route_drop_channel_closed_total 141
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 989912
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 736
telemt_desync_full_logged_total 229
telemt_desync_suppressed_total 507
telemt_desync_frames_bucket_total{bucket="1_2"} 189
telemt_desync_frames_bucket_total{bucket="3_10"} 266
telemt_desync_frames_bucket_total{bucket="gt_10"} 281
telemt_pool_swap_total 124
telemt_me_writer_removed_unexpected_total 22898
telemt_me_refill_failed_total 109
telemt_me_writer_restored_same_endpoint_total 22483
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 388
telemt_user_connections_total{user="hello"} 848490
telemt_user_connections_current{user="hello"} 702
telemt_user_octets_from_client{user="hello"} 18000457644 (16.76 GB)
telemt_user_octets_to_client{user="hello"} 486572244228 (453.16 GB)
telemt_user_unique_ips_current{user="hello"} 245
telemt_user_unique_ips_recent_window{user="hello"} 109
```