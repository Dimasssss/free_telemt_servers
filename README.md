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

# Server Metrics 2026-03-14 04:04:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 160266.9 (44h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 623159
telemt_connections_bad_total 30968
telemt_handshake_timeouts_total 12936
telemt_upstream_connect_attempt_total 40970
telemt_upstream_connect_success_total 40762
telemt_upstream_connect_fail_total 208
telemt_upstream_connect_attempts_per_request{bucket="1"} 40970
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18616
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21995
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 208
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5547
telemt_me_reconnect_attempts_total 37065
telemt_me_reconnect_success_total 32382
telemt_me_reader_eof_total 34603
telemt_me_idle_close_by_peer_total 34602
telemt_me_route_drop_no_conn_total 202340
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 527691
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1800
telemt_desync_full_logged_total 608
telemt_desync_suppressed_total 1192
telemt_desync_frames_bucket_total{bucket="1_2"} 380
telemt_desync_frames_bucket_total{bucket="3_10"} 668
telemt_desync_frames_bucket_total{bucket="gt_10"} 752
telemt_pool_swap_total 146
telemt_me_writer_removed_unexpected_total 32882
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 32362
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 500
telemt_user_connections_total{user="hello"} 527581
telemt_user_connections_current{user="hello"} 267
telemt_user_octets_from_client{user="hello"} 15724907926 (14.64 GB)
telemt_user_octets_to_client{user="hello"} 257341723176 (239.67 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 160159.8 (44h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 314762
telemt_connections_bad_total 2266
telemt_handshake_timeouts_total 1996
telemt_upstream_connect_attempt_total 146628
telemt_upstream_connect_success_total 145456
telemt_upstream_connect_fail_total 1172
telemt_upstream_connect_attempts_per_request{bucket="1"} 146628
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 108502
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34537
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2417
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1172
telemt_me_keepalive_timeout_total 3863
telemt_me_reconnect_attempts_total 168491
telemt_me_reconnect_success_total 34179
telemt_me_reader_eof_total 39266
telemt_me_idle_close_by_peer_total 39266
telemt_me_route_drop_no_conn_total 99255
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 195305
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 41
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
telemt_me_writer_removed_unexpected_total 38697
telemt_me_refill_failed_total 4191
telemt_me_writer_restored_same_endpoint_total 34162
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4518
telemt_user_connections_total{user="hello"} 298417
telemt_user_connections_current{user="hello"} 87
telemt_user_octets_from_client{user="hello"} 3117440283 (2.90 GB)
telemt_user_octets_to_client{user="hello"} 96704285443 (90.06 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 160126.3 (44h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 367674
telemt_connections_bad_total 2917
telemt_handshake_timeouts_total 34787
telemt_upstream_connect_attempt_total 42431
telemt_upstream_connect_success_total 42425
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 42431
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19389
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22976
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3344
telemt_me_reconnect_attempts_total 35694
telemt_me_reconnect_success_total 34418
telemt_me_reader_eof_total 36987
telemt_me_idle_close_by_peer_total 36987
telemt_me_route_drop_no_conn_total 131386
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 317224
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
telemt_pool_swap_total 151
telemt_me_writer_removed_unexpected_total 34822
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 34397
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 404
telemt_user_connections_total{user="hello"} 317031
telemt_user_connections_current{user="hello"} 101
telemt_user_octets_from_client{user="hello"} 12675297992 (11.80 GB)
telemt_user_octets_to_client{user="hello"} 127882461296 (119.10 GB)
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 160099.0 (44h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 469191
telemt_connections_bad_total 15548
telemt_handshake_timeouts_total 4401
telemt_upstream_connect_attempt_total 72172
telemt_upstream_connect_success_total 61668
telemt_upstream_connect_fail_total 10504
telemt_upstream_connect_attempts_per_request{bucket="1"} 72172
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36819
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24510
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 330
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10504
telemt_me_keepalive_timeout_total 5145
telemt_me_reconnect_attempts_total 140715
telemt_me_reconnect_success_total 34669
telemt_me_reader_eof_total 39041
telemt_me_idle_close_by_peer_total 39033
telemt_me_route_drop_no_conn_total 167519
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 398108
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1709
telemt_desync_full_logged_total 502
telemt_desync_suppressed_total 1207
telemt_desync_frames_bucket_total{bucket="1_2"} 401
telemt_desync_frames_bucket_total{bucket="3_10"} 646
telemt_desync_frames_bucket_total{bucket="gt_10"} 662
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 38380
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 34659
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3711
telemt_user_connections_total{user="hello"} 416938
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 9169039835 (8.54 GB)
telemt_user_octets_to_client{user="hello"} 162459689004 (151.30 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 110270.5 (30h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 182143
telemt_connections_bad_total 26313
telemt_handshake_timeouts_total 1630
telemt_upstream_connect_attempt_total 39875
telemt_upstream_connect_success_total 39506
telemt_upstream_connect_fail_total 369
telemt_upstream_connect_attempts_per_request{bucket="1"} 39875
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19915
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19460
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 131
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 369
telemt_me_keepalive_timeout_total 2374
telemt_me_reconnect_attempts_total 42541
telemt_me_reconnect_success_total 29121
telemt_me_reader_eof_total 31164
telemt_me_idle_close_by_peer_total 31164
telemt_me_route_drop_no_conn_total 53966
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 144274
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
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 29805
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 29103
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 684
telemt_user_connections_total{user="hello"} 149033
telemt_user_connections_current{user="hello"} 41
telemt_user_octets_from_client{user="hello"} 2203975809 (2.05 GB)
telemt_user_octets_to_client{user="hello"} 68764783095 (64.04 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 160055.1 (44h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 912186
telemt_connections_bad_total 28157
telemt_handshake_timeouts_total 25451
telemt_upstream_connect_attempt_total 33264
telemt_upstream_connect_success_total 33090
telemt_upstream_connect_fail_total 174
telemt_upstream_connect_attempts_per_request{bucket="1"} 33264
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15499
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17550
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 174
telemt_me_keepalive_timeout_total 3513
telemt_me_reconnect_attempts_total 29849
telemt_me_reconnect_success_total 25180
telemt_me_reader_eof_total 26987
telemt_me_idle_close_by_peer_total 26984
telemt_me_route_drop_no_conn_total 434526
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 851878
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 759
telemt_desync_full_logged_total 249
telemt_desync_suppressed_total 510
telemt_desync_frames_bucket_total{bucket="1_2"} 256
telemt_desync_frames_bucket_total{bucket="3_10"} 247
telemt_desync_frames_bucket_total{bucket="gt_10"} 256
telemt_pool_swap_total 150
telemt_me_writer_removed_unexpected_total 25647
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 25173
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 467
telemt_user_connections_total{user="hello"} 824543
telemt_user_connections_current{user="hello"} 280
telemt_user_octets_from_client{user="hello"} 14382411120 (13.39 GB)
telemt_user_octets_to_client{user="hello"} 414351869308 (385.90 GB)
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 36
```