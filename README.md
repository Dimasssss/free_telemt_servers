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

# Server Metrics 2026-03-13 19:30:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 129405.1 (35h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 549247
telemt_connections_bad_total 13186
telemt_handshake_timeouts_total 12444
telemt_upstream_connect_attempt_total 32726
telemt_upstream_connect_success_total 32559
telemt_upstream_connect_fail_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 32726
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14987
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17430
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 142
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 167
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5045
telemt_me_reconnect_attempts_total 30363
telemt_me_reconnect_success_total 25712
telemt_me_reader_eof_total 27461
telemt_me_idle_close_by_peer_total 27460
telemt_me_route_drop_no_conn_total 180880
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 474207
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1534
telemt_desync_full_logged_total 522
telemt_desync_suppressed_total 1012
telemt_desync_frames_bucket_total{bucket="1_2"} 332
telemt_desync_frames_bucket_total{bucket="3_10"} 564
telemt_desync_frames_bucket_total{bucket="gt_10"} 638
telemt_pool_swap_total 116
telemt_me_writer_removed_unexpected_total 26145
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 25696
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 433
telemt_user_connections_total{user="hello"} 474149
telemt_user_connections_current{user="hello"} 311
telemt_user_octets_from_client{user="hello"} 8766169322 (8.16 GB)
telemt_user_octets_to_client{user="hello"} 226190031972 (210.66 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 129298.9 (35h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 274525
telemt_connections_bad_total 2096
telemt_handshake_timeouts_total 1871
telemt_upstream_connect_attempt_total 125793
telemt_upstream_connect_success_total 124858
telemt_upstream_connect_fail_total 935
telemt_upstream_connect_attempts_per_request{bucket="1"} 125793
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 94677
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27999
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2182
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 935
telemt_me_keepalive_timeout_total 3599
telemt_me_reconnect_attempts_total 135174
telemt_me_reconnect_success_total 26267
telemt_me_reader_eof_total 30406
telemt_me_idle_close_by_peer_total 30406
telemt_me_route_drop_no_conn_total 83540
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 168199
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 32
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
telemt_me_writer_removed_unexpected_total 29913
telemt_me_refill_failed_total 3398
telemt_me_writer_restored_same_endpoint_total 26250
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3646
telemt_user_connections_total{user="hello"} 260128
telemt_user_connections_current{user="hello"} 167
telemt_user_octets_from_client{user="hello"} 2679742487 (2.50 GB)
telemt_user_octets_to_client{user="hello"} 78490638880 (73.10 GB)
telemt_user_msgs_from_client{user="hello"} 1448090
telemt_user_msgs_to_client{user="hello"} 8103679
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 129262.4 (35h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 321561
telemt_connections_bad_total 2632
telemt_handshake_timeouts_total 21802
telemt_upstream_connect_attempt_total 34350
telemt_upstream_connect_success_total 34345
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 34350
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15894
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18412
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2772
telemt_me_reconnect_attempts_total 29087
telemt_me_reconnect_success_total 27849
telemt_me_reader_eof_total 29879
telemt_me_idle_close_by_peer_total 29879
telemt_me_route_drop_no_conn_total 115164
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 285922
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 119
telemt_me_writer_removed_unexpected_total 28165
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 27829
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 316
telemt_user_connections_total{user="hello"} 285831
telemt_user_connections_current{user="hello"} 141
telemt_user_octets_from_client{user="hello"} 11715162544 (10.91 GB)
telemt_user_octets_to_client{user="hello"} 120243731604 (111.99 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 129237.9 (35h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 426493
telemt_connections_bad_total 15182
telemt_handshake_timeouts_total 4120
telemt_upstream_connect_attempt_total 62145
telemt_upstream_connect_success_total 51864
telemt_upstream_connect_fail_total 10281
telemt_upstream_connect_attempts_per_request{bucket="1"} 62145
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32570
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18990
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 295
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10281
telemt_me_keepalive_timeout_total 4721
telemt_me_reconnect_attempts_total 117003
telemt_me_reconnect_success_total 26381
telemt_me_reader_eof_total 29977
telemt_me_idle_close_by_peer_total 29970
telemt_me_route_drop_no_conn_total 147423
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 357821
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1442
telemt_desync_full_logged_total 429
telemt_desync_suppressed_total 1013
telemt_desync_frames_bucket_total{bucket="1_2"} 349
telemt_desync_frames_bucket_total{bucket="3_10"} 550
telemt_desync_frames_bucket_total{bucket="gt_10"} 543
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 29547
telemt_me_refill_failed_total 2826
telemt_me_writer_restored_same_endpoint_total 26371
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3166
telemt_user_connections_total{user="hello"} 376699
telemt_user_connections_current{user="hello"} 187
telemt_user_octets_from_client{user="hello"} 8550074731 (7.96 GB)
telemt_user_octets_to_client{user="hello"} 135187476900 (125.90 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 79409.4 (22h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 134151
telemt_connections_bad_total 16533
telemt_handshake_timeouts_total 1422
telemt_upstream_connect_attempt_total 30494
telemt_upstream_connect_success_total 30203
telemt_upstream_connect_fail_total 291
telemt_upstream_connect_attempts_per_request{bucket="1"} 30494
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15604
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14498
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 291
telemt_me_keepalive_timeout_total 1227
telemt_me_reconnect_attempts_total 34708
telemt_me_reconnect_success_total 21317
telemt_me_reader_eof_total 22847
telemt_me_idle_close_by_peer_total 22847
telemt_me_route_drop_no_conn_total 41931
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 106941
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 594
telemt_desync_full_logged_total 136
telemt_desync_suppressed_total 458
telemt_desync_frames_bucket_total{bucket="1_2"} 83
telemt_desync_frames_bucket_total{bucket="3_10"} 297
telemt_desync_frames_bucket_total{bucket="gt_10"} 214
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 21934
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 21299
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 617
telemt_user_connections_total{user="hello"} 111836
telemt_user_connections_current{user="hello"} 98
telemt_user_octets_from_client{user="hello"} 1293261833 (1.20 GB)
telemt_user_octets_to_client{user="hello"} 41858570467 (38.98 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 129194.1 (35h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 791432
telemt_connections_bad_total 24786
telemt_handshake_timeouts_total 24862
telemt_upstream_connect_attempt_total 26670
telemt_upstream_connect_success_total 26530
telemt_upstream_connect_fail_total 140
telemt_upstream_connect_attempts_per_request{bucket="1"} 26670
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12396
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14098
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 140
telemt_me_keepalive_timeout_total 3050
telemt_me_reconnect_attempts_total 24764
telemt_me_reconnect_success_total 20118
telemt_me_reader_eof_total 21589
telemt_me_idle_close_by_peer_total 21586
telemt_me_route_drop_no_conn_total 376505
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 741895
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 691
telemt_desync_full_logged_total 225
telemt_desync_suppressed_total 466
telemt_desync_frames_bucket_total{bucket="1_2"} 247
telemt_desync_frames_bucket_total{bucket="3_10"} 226
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 120
telemt_me_writer_removed_unexpected_total 20532
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 20111
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 414
telemt_user_connections_total{user="hello"} 714765
telemt_user_connections_current{user="hello"} 433
telemt_user_octets_from_client{user="hello"} 12388807676 (11.54 GB)
telemt_user_octets_to_client{user="hello"} 352157912852 (327.97 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 56
```