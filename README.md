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

# Server Metrics 2026-03-14 03:28:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 158126.7 (43h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 615482
telemt_connections_bad_total 28858
telemt_handshake_timeouts_total 12931
telemt_upstream_connect_attempt_total 40428
telemt_upstream_connect_success_total 40225
telemt_upstream_connect_fail_total 203
telemt_upstream_connect_attempts_per_request{bucket="1"} 40428
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18380
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21695
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 203
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5543
telemt_me_reconnect_attempts_total 36638
telemt_me_reconnect_success_total 31957
telemt_me_reader_eof_total 34146
telemt_me_idle_close_by_peer_total 34145
telemt_me_route_drop_no_conn_total 200312
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 522349
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1730
telemt_desync_full_logged_total 592
telemt_desync_suppressed_total 1138
telemt_desync_frames_bucket_total{bucket="1_2"} 370
telemt_desync_frames_bucket_total{bucket="3_10"} 651
telemt_desync_frames_bucket_total{bucket="gt_10"} 709
telemt_pool_swap_total 144
telemt_me_writer_removed_unexpected_total 32452
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 31937
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 495
telemt_user_connections_total{user="hello"} 522240
telemt_user_connections_current{user="hello"} 255
telemt_user_octets_from_client{user="hello"} 15688728302 (14.61 GB)
telemt_user_octets_to_client{user="hello"} 256038336320 (238.45 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 158019.8 (43h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 312272
telemt_connections_bad_total 2265
telemt_handshake_timeouts_total 1944
telemt_upstream_connect_attempt_total 145763
telemt_upstream_connect_success_total 144603
telemt_upstream_connect_fail_total 1160
telemt_upstream_connect_attempts_per_request{bucket="1"} 145763
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 108178
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34008
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2417
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1160
telemt_me_keepalive_timeout_total 3838
telemt_me_reconnect_attempts_total 165388
telemt_me_reconnect_success_total 33412
telemt_me_reader_eof_total 38421
telemt_me_idle_close_by_peer_total 38421
telemt_me_route_drop_no_conn_total 98653
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 192989
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
telemt_me_writer_removed_unexpected_total 37852
telemt_me_refill_failed_total 4118
telemt_me_writer_restored_same_endpoint_total 33395
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4440
telemt_user_connections_total{user="hello"} 296101
telemt_user_connections_current{user="hello"} 94
telemt_user_octets_from_client{user="hello"} 3100961187 (2.89 GB)
telemt_user_octets_to_client{user="hello"} 94962562255 (88.44 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 157983.5 (43h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 365419
telemt_connections_bad_total 2910
telemt_handshake_timeouts_total 34628
telemt_upstream_connect_attempt_total 41910
telemt_upstream_connect_success_total 41904
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 41910
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19168
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22679
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3316
telemt_me_reconnect_attempts_total 35259
telemt_me_reconnect_success_total 33986
telemt_me_reader_eof_total 36520
telemt_me_idle_close_by_peer_total 36520
telemt_me_route_drop_no_conn_total 130442
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 315213
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
telemt_pool_swap_total 149
telemt_me_writer_removed_unexpected_total 34382
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 33965
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 396
telemt_user_connections_total{user="hello"} 315031
telemt_user_connections_current{user="hello"} 61
telemt_user_octets_from_client{user="hello"} 12642547992 (11.77 GB)
telemt_user_octets_to_client{user="hello"} 127616677604 (118.85 GB)
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 157958.9 (43h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 466753
telemt_connections_bad_total 15543
telemt_handshake_timeouts_total 4397
telemt_upstream_connect_attempt_total 71423
telemt_upstream_connect_success_total 60926
telemt_upstream_connect_fail_total 10497
telemt_upstream_connect_attempts_per_request{bucket="1"} 71423
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36507
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24082
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 328
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10497
telemt_me_keepalive_timeout_total 5125
telemt_me_reconnect_attempts_total 140061
telemt_me_reconnect_success_total 34015
telemt_me_reader_eof_total 38329
telemt_me_idle_close_by_peer_total 38321
telemt_me_route_drop_no_conn_total 165570
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 395803
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
telemt_me_writer_removed_unexpected_total 37724
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 34005
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3709
telemt_user_connections_total{user="hello"} 414633
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 9113936271 (8.49 GB)
telemt_user_octets_to_client{user="hello"} 161242707200 (150.17 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 108130.6 (30h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 179505
telemt_connections_bad_total 25924
telemt_handshake_timeouts_total 1571
telemt_upstream_connect_attempt_total 39167
telemt_upstream_connect_success_total 38802
telemt_upstream_connect_fail_total 365
telemt_upstream_connect_attempts_per_request{bucket="1"} 39167
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19596
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19077
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 129
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 365
telemt_me_keepalive_timeout_total 2356
telemt_me_reconnect_attempts_total 41924
telemt_me_reconnect_success_total 28504
telemt_me_reader_eof_total 30502
telemt_me_idle_close_by_peer_total 30502
telemt_me_route_drop_no_conn_total 53142
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 142152
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
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 29181
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 28486
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 677
telemt_user_connections_total{user="hello"} 146917
telemt_user_connections_current{user="hello"} 64
telemt_user_octets_from_client{user="hello"} 2171265605 (2.02 GB)
telemt_user_octets_to_client{user="hello"} 68003414943 (63.33 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 157914.9 (43h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 902792
telemt_connections_bad_total 28010
telemt_handshake_timeouts_total 25402
telemt_upstream_connect_attempt_total 32840
telemt_upstream_connect_success_total 32669
telemt_upstream_connect_fail_total 171
telemt_upstream_connect_attempts_per_request{bucket="1"} 32840
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15300
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17328
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 171
telemt_me_keepalive_timeout_total 3504
telemt_me_reconnect_attempts_total 29514
telemt_me_reconnect_success_total 24846
telemt_me_reader_eof_total 26631
telemt_me_idle_close_by_peer_total 26628
telemt_me_route_drop_no_conn_total 430295
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 844243
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 756
telemt_desync_full_logged_total 247
telemt_desync_suppressed_total 509
telemt_desync_frames_bucket_total{bucket="1_2"} 256
telemt_desync_frames_bucket_total{bucket="3_10"} 246
telemt_desync_frames_bucket_total{bucket="gt_10"} 254
telemt_pool_swap_total 148
telemt_me_writer_removed_unexpected_total 25308
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 24839
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 462
telemt_user_connections_total{user="hello"} 816908
telemt_user_connections_current{user="hello"} 303
telemt_user_octets_from_client{user="hello"} 14341374356 (13.36 GB)
telemt_user_octets_to_client{user="hello"} 412971977316 (384.61 GB)
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 33
```