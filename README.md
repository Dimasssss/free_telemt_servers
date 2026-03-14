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

# Server Metrics 2026-03-14 02:58:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 156293.7 (43h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 606850
telemt_connections_bad_total 23527
telemt_handshake_timeouts_total 12923
telemt_upstream_connect_attempt_total 39957
telemt_upstream_connect_success_total 39758
telemt_upstream_connect_fail_total 199
telemt_upstream_connect_attempts_per_request{bucket="1"} 39957
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18183
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21425
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 199
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5536
telemt_me_reconnect_attempts_total 36257
telemt_me_reconnect_success_total 31577
telemt_me_reader_eof_total 33733
telemt_me_idle_close_by_peer_total 33732
telemt_me_route_drop_no_conn_total 198753
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 519130
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1690
telemt_desync_full_logged_total 583
telemt_desync_suppressed_total 1107
telemt_desync_frames_bucket_total{bucket="1_2"} 358
telemt_desync_frames_bucket_total{bucket="3_10"} 641
telemt_desync_frames_bucket_total{bucket="gt_10"} 691
telemt_pool_swap_total 142
telemt_me_writer_removed_unexpected_total 32067
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 31557
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 490
telemt_user_connections_total{user="hello"} 519021
telemt_user_connections_current{user="hello"} 230
telemt_user_octets_from_client{user="hello"} 15654740670 (14.58 GB)
telemt_user_octets_to_client{user="hello"} 255204024704 (237.68 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 156186.7 (43h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 310392
telemt_connections_bad_total 2264
telemt_handshake_timeouts_total 1941
telemt_upstream_connect_attempt_total 145031
telemt_upstream_connect_success_total 143882
telemt_upstream_connect_fail_total 1149
telemt_upstream_connect_attempts_per_request{bucket="1"} 145031
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 107861
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33604
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2417
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1149
telemt_me_keepalive_timeout_total 3832
telemt_me_reconnect_attempts_total 164753
telemt_me_reconnect_success_total 32778
telemt_me_reader_eof_total 37778
telemt_me_idle_close_by_peer_total 37778
telemt_me_route_drop_no_conn_total 98149
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 191176
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 40
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
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 37209
telemt_me_refill_failed_total 4118
telemt_me_writer_restored_same_endpoint_total 32761
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4431
telemt_user_connections_total{user="hello"} 294288
telemt_user_connections_current{user="hello"} 92
telemt_user_octets_from_client{user="hello"} 3080524847 (2.87 GB)
telemt_user_octets_to_client{user="hello"} 93078791907 (86.69 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 156150.4 (43h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 363390
telemt_connections_bad_total 2832
telemt_handshake_timeouts_total 34048
telemt_upstream_connect_attempt_total 41442
telemt_upstream_connect_success_total 41436
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 41442
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18939
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22440
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3308
telemt_me_reconnect_attempts_total 34877
telemt_me_reconnect_success_total 33606
telemt_me_reader_eof_total 36112
telemt_me_idle_close_by_peer_total 36112
telemt_me_route_drop_no_conn_total 129797
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 313912
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
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
telemt_pool_swap_total 147
telemt_me_writer_removed_unexpected_total 33998
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 33585
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 392
telemt_user_connections_total{user="hello"} 313733
telemt_user_connections_current{user="hello"} 72
telemt_user_octets_from_client{user="hello"} 12635578348 (11.77 GB)
telemt_user_octets_to_client{user="hello"} 127401746728 (118.65 GB)
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 156125.7 (43h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 464622
telemt_connections_bad_total 15380
telemt_handshake_timeouts_total 4388
telemt_upstream_connect_attempt_total 70669
telemt_upstream_connect_success_total 60189
telemt_upstream_connect_fail_total 10480
telemt_upstream_connect_attempts_per_request{bucket="1"} 70669
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36148
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23706
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 326
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10480
telemt_me_keepalive_timeout_total 5110
telemt_me_reconnect_attempts_total 139411
telemt_me_reconnect_success_total 33367
telemt_me_reader_eof_total 37677
telemt_me_idle_close_by_peer_total 37669
telemt_me_route_drop_no_conn_total 164711
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 393982
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1708
telemt_desync_full_logged_total 501
telemt_desync_suppressed_total 1207
telemt_desync_frames_bucket_total{bucket="1_2"} 400
telemt_desync_frames_bucket_total{bucket="3_10"} 646
telemt_desync_frames_bucket_total{bucket="gt_10"} 662
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 37072
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 33357
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3705
telemt_user_connections_total{user="hello"} 412815
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 9102317739 (8.48 GB)
telemt_user_octets_to_client{user="hello"} 160128045580 (149.13 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 106297.3 (29h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 177074
telemt_connections_bad_total 25593
telemt_handshake_timeouts_total 1564
telemt_upstream_connect_attempt_total 38648
telemt_upstream_connect_success_total 38289
telemt_upstream_connect_fail_total 359
telemt_upstream_connect_attempts_per_request{bucket="1"} 38648
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19359
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18802
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 128
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 359
telemt_me_keepalive_timeout_total 2349
telemt_me_reconnect_attempts_total 41501
telemt_me_reconnect_success_total 28083
telemt_me_reader_eof_total 30048
telemt_me_idle_close_by_peer_total 30048
telemt_me_route_drop_no_conn_total 52379
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 140092
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 622
telemt_desync_full_logged_total 146
telemt_desync_suppressed_total 476
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 78
telemt_me_writer_removed_unexpected_total 28756
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 28065
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 673
telemt_user_connections_total{user="hello"} 144860
telemt_user_connections_current{user="hello"} 45
telemt_user_octets_from_client{user="hello"} 2087770757 (1.94 GB)
telemt_user_octets_to_client{user="hello"} 65487861423 (60.99 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 156081.8 (43h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 896285
telemt_connections_bad_total 27813
telemt_handshake_timeouts_total 25368
telemt_upstream_connect_attempt_total 32417
telemt_upstream_connect_success_total 32246
telemt_upstream_connect_fail_total 171
telemt_upstream_connect_attempts_per_request{bucket="1"} 32417
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15097
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17108
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 171
telemt_me_keepalive_timeout_total 3501
telemt_me_reconnect_attempts_total 29177
telemt_me_reconnect_success_total 24510
telemt_me_reader_eof_total 26271
telemt_me_idle_close_by_peer_total 26268
telemt_me_route_drop_no_conn_total 427182
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 838044
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 724
telemt_desync_full_logged_total 235
telemt_desync_suppressed_total 489
telemt_desync_frames_bucket_total{bucket="1_2"} 254
telemt_desync_frames_bucket_total{bucket="3_10"} 240
telemt_desync_frames_bucket_total{bucket="gt_10"} 230
telemt_pool_swap_total 146
telemt_me_writer_removed_unexpected_total 24971
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 24503
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 461
telemt_user_connections_total{user="hello"} 810802
telemt_user_connections_current{user="hello"} 251
telemt_user_octets_from_client{user="hello"} 14294634116 (13.31 GB)
telemt_user_octets_to_client{user="hello"} 411171244096 (382.93 GB)
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 38
```