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

# Server Metrics 2026-03-14 22:05:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 31737.3 (8h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 147622
telemt_connections_bad_total 16509
telemt_handshake_timeouts_total 1574
telemt_upstream_connect_attempt_total 7206
telemt_upstream_connect_success_total 7204
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 7206
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3397
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3720
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 5612
telemt_me_reconnect_success_total 5572
telemt_me_reader_eof_total 5930
telemt_me_idle_close_by_peer_total 5930
telemt_me_route_drop_no_conn_total 53205
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 122974
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 584
telemt_desync_full_logged_total 203
telemt_desync_suppressed_total 381
telemt_desync_frames_bucket_total{bucket="1_2"} 130
telemt_desync_frames_bucket_total{bucket="3_10"} 213
telemt_desync_frames_bucket_total{bucket="gt_10"} 241
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 5661
telemt_me_writer_restored_same_endpoint_total 5554
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 122894
telemt_user_connections_current{user="hello"} 261
telemt_user_octets_from_client{user="hello"} 2653688272 (2.47 GB)
telemt_user_octets_to_client{user="hello"} 74323995304 (69.22 GB)
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 31735.4 (8h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61142
telemt_connections_bad_total 738
telemt_handshake_timeouts_total 1091
telemt_upstream_connect_attempt_total 8265
telemt_upstream_connect_success_total 8213
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 8265
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3420
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4657
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 136
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 147
telemt_me_reconnect_attempts_total 9163
telemt_me_reconnect_success_total 6578
telemt_me_reader_eof_total 7017
telemt_me_idle_close_by_peer_total 7017
telemt_me_route_drop_no_conn_total 32681
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 57015
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 6746
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 6573
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 168
telemt_user_connections_total{user="hello"} 56936
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 1416008112 (1.32 GB)
telemt_user_octets_to_client{user="hello"} 26572275880 (24.75 GB)
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 31739.9 (8h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69408
telemt_connections_bad_total 395
telemt_handshake_timeouts_total 1918
telemt_upstream_connect_attempt_total 10376
telemt_upstream_connect_success_total 10270
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 10376
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4748
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5509
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 106187
telemt_me_reconnect_success_total 8321
telemt_me_reader_eof_total 8904
telemt_me_idle_close_by_peer_total 8904
telemt_me_route_drop_no_conn_total 25676
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 63631
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 8607
telemt_me_refill_failed_total 3169
telemt_me_writer_restored_same_endpoint_total 8275
telemt_me_writer_restored_fallback_total 46
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 286
telemt_user_connections_total{user="hello"} 63694
telemt_user_connections_current{user="hello"} 87
telemt_user_octets_from_client{user="hello"} 3982294805 (3.71 GB)
telemt_user_octets_to_client{user="hello"} 50714612162 (47.23 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 31744.9 (8h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87067
telemt_connections_bad_total 215
telemt_handshake_timeouts_total 620
telemt_upstream_connect_attempt_total 7762
telemt_upstream_connect_success_total 7715
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 7762
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3587
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4097
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 212
telemt_me_reconnect_attempts_total 5948
telemt_me_reconnect_success_total 5918
telemt_me_reader_eof_total 6252
telemt_me_idle_close_by_peer_total 6252
telemt_me_route_drop_no_conn_total 37978
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 82570
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 663
telemt_desync_full_logged_total 171
telemt_desync_suppressed_total 492
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 279
telemt_desync_frames_bucket_total{bucket="gt_10"} 264
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 5983
telemt_me_writer_restored_same_endpoint_total 5916
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 82614
telemt_user_connections_current{user="hello"} 121
telemt_user_octets_from_client{user="hello"} 1404329416 (1.31 GB)
telemt_user_octets_to_client{user="hello"} 30258349154 (28.18 GB)
telemt_user_msgs_from_client{user="hello"} 473
telemt_user_msgs_to_client{user="hello"} 2783
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 31737.9 (8h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66175
telemt_connections_bad_total 6175
telemt_handshake_timeouts_total 3390
telemt_upstream_connect_attempt_total 7829
telemt_upstream_connect_success_total 7736
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 7829
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3500
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4185
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 235
telemt_me_reconnect_attempts_total 12640
telemt_me_reconnect_success_total 6099
telemt_me_reader_eof_total 6592
telemt_me_idle_close_by_peer_total 6592
telemt_me_route_drop_no_conn_total 21265
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 53343
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 270
telemt_desync_full_logged_total 41
telemt_desync_suppressed_total 229
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 96
telemt_desync_frames_bucket_total{bucket="gt_10"} 136
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 6361
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 6095
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 262
telemt_user_connections_total{user="hello"} 53329
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 1418563364 (1.32 GB)
telemt_user_octets_to_client{user="hello"} 32352579320 (30.13 GB)
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 31737.4 (8h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 222191
telemt_connections_bad_total 7769
telemt_handshake_timeouts_total 2759
telemt_upstream_connect_attempt_total 6368
telemt_upstream_connect_success_total 6255
telemt_upstream_connect_fail_total 113
telemt_upstream_connect_attempts_per_request{bucket="1"} 6368
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3054
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3196
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 113
telemt_me_keepalive_timeout_total 266
telemt_me_reconnect_attempts_total 9634
telemt_me_reconnect_success_total 4624
telemt_me_reader_eof_total 5005
telemt_me_idle_close_by_peer_total 5005
telemt_me_route_drop_no_conn_total 124194
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 205204
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 116
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 84
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 4838
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 4620
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 214
telemt_user_connections_total{user="hello"} 201687
telemt_user_connections_current{user="hello"} 310
telemt_user_octets_from_client{user="hello"} 6346767388 (5.91 GB)
telemt_user_octets_to_client{user="hello"} 112294271592 (104.58 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 24
```