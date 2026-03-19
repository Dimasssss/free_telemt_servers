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

# Server Metrics 2026-03-19 10:34:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 45955.0 (12h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1037290
telemt_connections_bad_total 90608
telemt_connections_current 1557
telemt_connections_me_current 1557
telemt_handshake_timeouts_total 37124
telemt_upstream_connect_attempt_total 8695
telemt_upstream_connect_success_total 8540
telemt_upstream_connect_fail_total 154
telemt_upstream_connect_attempts_per_request{bucket="1"} 8694
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4131
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4406
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 154
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 91
telemt_me_reconnect_attempts_total 7399
telemt_me_reconnect_success_total 6238
telemt_me_reader_eof_total 6605
telemt_me_idle_close_by_peer_total 6602
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 368808
telemt_me_route_drop_channel_closed_total 156
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 799351
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 30
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4635
telemt_desync_full_logged_total 1418
telemt_desync_suppressed_total 3217
telemt_desync_frames_bucket_total{bucket="1_2"} 1535
telemt_desync_frames_bucket_total{bucket="3_10"} 1691
telemt_desync_frames_bucket_total{bucket="gt_10"} 1409
telemt_pool_swap_total 38
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 6353
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 6218
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 793504
telemt_user_connections_current{user="hello"} 1557
telemt_user_octets_from_client{user="hello"} 12179306072 (11.34 GB)
telemt_user_octets_to_client{user="hello"} 250226121116 (233.04 GB)
telemt_user_unique_ips_current{user="hello"} 539
telemt_user_unique_ips_recent_window{user="hello"} 367
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 45959.4 (12h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2591506
telemt_connections_bad_total 161960
telemt_connections_current 3675
telemt_connections_me_current 3675
telemt_handshake_timeouts_total 54764
telemt_upstream_connect_attempt_total 8783
telemt_upstream_connect_success_total 8619
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 8783
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4334
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4260
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 8649
telemt_me_reconnect_success_total 6293
telemt_me_reader_eof_total 6685
telemt_me_idle_close_by_peer_total 6684
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 1246065
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2153316
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9668
telemt_desync_full_logged_total 3208
telemt_desync_suppressed_total 6460
telemt_desync_frames_bucket_total{bucket="1_2"} 1800
telemt_desync_frames_bucket_total{bucket="3_10"} 3801
telemt_desync_frames_bucket_total{bucket="gt_10"} 4067
telemt_pool_swap_total 33
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 6483
telemt_me_refill_failed_total 73
telemt_me_writer_restored_same_endpoint_total 6271
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 190
telemt_user_connections_total{user="hello"} 2153060
telemt_user_connections_current{user="hello"} 3675
telemt_user_octets_from_client{user="hello"} 32711481804 (30.46 GB)
telemt_user_octets_to_client{user="hello"} 757414118860 (705.40 GB)
telemt_user_unique_ips_current{user="hello"} 1207
telemt_user_unique_ips_recent_window{user="hello"} 1131
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 45956.3 (12h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2204691
telemt_connections_bad_total 257960
telemt_connections_current 2952
telemt_connections_me_current 2952
telemt_handshake_timeouts_total 48821
telemt_upstream_connect_attempt_total 8149
telemt_upstream_connect_success_total 8149
telemt_upstream_connect_attempts_per_request{bucket="1"} 8149
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4278
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3855
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 5866
telemt_me_reconnect_success_total 5830
telemt_me_reader_eof_total 6171
telemt_me_idle_close_by_peer_total 6171
telemt_me_route_drop_no_conn_total 1351520
telemt_me_route_drop_channel_closed_total 67
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1731706
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7427
telemt_desync_full_logged_total 2373
telemt_desync_suppressed_total 5054
telemt_desync_frames_bucket_total{bucket="1_2"} 1650
telemt_desync_frames_bucket_total{bucket="3_10"} 2742
telemt_desync_frames_bucket_total{bucket="gt_10"} 3035
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 5933
telemt_me_writer_restored_same_endpoint_total 5814
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 1730070
telemt_user_connections_current{user="hello"} 2952
telemt_user_octets_from_client{user="hello"} 24741846104 (23.04 GB)
telemt_user_octets_to_client{user="hello"} 750018291344 (698.51 GB)
telemt_user_unique_ips_current{user="hello"} 1025
telemt_user_unique_ips_recent_window{user="hello"} 469
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 46009.5 (12h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2185035
telemt_connections_bad_total 120144
telemt_connections_current 3060
telemt_connections_me_current 3060
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 57616
telemt_upstream_connect_attempt_total 16481
telemt_upstream_connect_success_total 16327
telemt_upstream_connect_fail_total 154
telemt_upstream_connect_attempts_per_request{bucket="1"} 16481
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11506
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4659
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 160
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 154
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 9139
telemt_me_reconnect_success_total 5818
telemt_me_reader_eof_total 6181
telemt_me_idle_close_by_peer_total 6180
telemt_me_route_drop_no_conn_total 1110039
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1658513
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6050
telemt_desync_full_logged_total 2053
telemt_desync_suppressed_total 3997
telemt_desync_frames_bucket_total{bucket="1_2"} 1254
telemt_desync_frames_bucket_total{bucket="3_10"} 2366
telemt_desync_frames_bucket_total{bucket="gt_10"} 2430
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 6236
telemt_me_refill_failed_total 97
telemt_me_writer_restored_same_endpoint_total 5794
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 295
telemt_me_writer_removed_unexpected_minus_restored_total 418
telemt_user_connections_total{user="hello"} 1664717
telemt_user_connections_current{user="hello"} 3060
telemt_user_octets_from_client{user="hello"} 19122453492 (17.81 GB)
telemt_user_octets_to_client{user="hello"} 479446074138 (446.52 GB)
telemt_user_msgs_from_client{user="hello"} 28643
telemt_user_msgs_to_client{user="hello"} 76631
telemt_user_unique_ips_current{user="hello"} 1033
telemt_user_unique_ips_recent_window{user="hello"} 506
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 45952.7 (12h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2591912
telemt_connections_bad_total 574260
telemt_connections_current 3607
telemt_connections_me_current 3607
telemt_handshake_timeouts_total 52094
telemt_upstream_connect_attempt_total 8052
telemt_upstream_connect_success_total 7996
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 8052
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4072
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3893
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 6882
telemt_me_reconnect_success_total 5682
telemt_me_reader_eof_total 6046
telemt_me_idle_close_by_peer_total 6045
telemt_me_route_drop_no_conn_total 966894
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1713027
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7630
telemt_desync_full_logged_total 2375
telemt_desync_suppressed_total 5255
telemt_desync_frames_bucket_total{bucket="1_2"} 1515
telemt_desync_frames_bucket_total{bucket="3_10"} 3297
telemt_desync_frames_bucket_total{bucket="gt_10"} 2818
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 5803
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 5658
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 121
telemt_user_connections_total{user="hello"} 1712132
telemt_user_connections_current{user="hello"} 3607
telemt_user_octets_from_client{user="hello"} 30032456744 (27.97 GB)
telemt_user_octets_to_client{user="hello"} 711578862764 (662.71 GB)
telemt_user_unique_ips_current{user="hello"} 1176
telemt_user_unique_ips_recent_window{user="hello"} 544
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 45964.6 (12h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 456062
telemt_connections_bad_total 18314
telemt_connections_current 830
telemt_connections_me_current 830
telemt_handshake_timeouts_total 3602
telemt_upstream_connect_attempt_total 11488
telemt_upstream_connect_success_total 11199
telemt_upstream_connect_fail_total 289
telemt_upstream_connect_attempts_per_request{bucket="1"} 11488
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5572
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5626
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 289
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 14277
telemt_me_reconnect_success_total 8887
telemt_me_reader_eof_total 9424
telemt_me_idle_close_by_peer_total 9424
telemt_me_route_drop_no_conn_total 232775
telemt_me_route_drop_channel_closed_total 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 411323
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 805
telemt_desync_full_logged_total 270
telemt_desync_suppressed_total 535
telemt_desync_frames_bucket_total{bucket="1_2"} 177
telemt_desync_frames_bucket_total{bucket="3_10"} 314
telemt_desync_frames_bucket_total{bucket="gt_10"} 314
telemt_pool_swap_total 22
telemt_pool_stale_pick_total 194
telemt_me_writer_removed_unexpected_total 9130
telemt_me_refill_failed_total 167
telemt_me_writer_restored_same_endpoint_total 8857
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 243
telemt_user_connections_total{user="hello"} 411278
telemt_user_connections_current{user="hello"} 829
telemt_user_octets_from_client{user="hello"} 6521421972 (6.07 GB)
telemt_user_octets_to_client{user="hello"} 157741965868 (146.91 GB)
telemt_user_unique_ips_current{user="hello"} 337
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 45955.2 (12h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1747242
telemt_connections_bad_total 143102
telemt_connections_current 3264
telemt_connections_me_current 3264
telemt_handshake_timeouts_total 69799
telemt_upstream_connect_attempt_total 9317
telemt_upstream_connect_success_total 9316
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9317
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5034
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4279
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 8342
telemt_me_reconnect_success_total 6987
telemt_me_reader_eof_total 7391
telemt_me_idle_close_by_peer_total 7390
telemt_me_route_drop_no_conn_total 686726
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1452711
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8293
telemt_desync_full_logged_total 2677
telemt_desync_suppressed_total 5616
telemt_desync_frames_bucket_total{bucket="1_2"} 1558
telemt_desync_frames_bucket_total{bucket="3_10"} 3141
telemt_desync_frames_bucket_total{bucket="gt_10"} 3594
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 7115
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 6972
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 128
telemt_user_connections_total{user="hello"} 1451487
telemt_user_connections_current{user="hello"} 3264
telemt_user_octets_from_client{user="hello"} 20449088800 (19.04 GB)
telemt_user_octets_to_client{user="hello"} 695655947136 (647.88 GB)
telemt_user_unique_ips_current{user="hello"} 1053
telemt_user_unique_ips_recent_window{user="hello"} 429
```