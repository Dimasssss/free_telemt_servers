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

# Server Metrics 2026-03-14 22:10:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 32043.4 (8h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 148456
telemt_connections_bad_total 16522
telemt_handshake_timeouts_total 1582
telemt_upstream_connect_attempt_total 7262
telemt_upstream_connect_success_total 7260
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 7262
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3421
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3752
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 228
telemt_me_reconnect_attempts_total 5668
telemt_me_reconnect_success_total 5627
telemt_me_reader_eof_total 5987
telemt_me_idle_close_by_peer_total 5987
telemt_me_route_drop_no_conn_total 53335
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 123760
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 596
telemt_desync_full_logged_total 205
telemt_desync_suppressed_total 391
telemt_desync_frames_bucket_total{bucket="1_2"} 133
telemt_desync_frames_bucket_total{bucket="3_10"} 215
telemt_desync_frames_bucket_total{bucket="gt_10"} 248
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 5718
telemt_me_writer_restored_same_endpoint_total 5609
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 123680
telemt_user_connections_current{user="hello"} 277
telemt_user_octets_from_client{user="hello"} 2661879920 (2.48 GB)
telemt_user_octets_to_client{user="hello"} 74715729644 (69.58 GB)
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 32041.7 (8h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61608
telemt_connections_bad_total 738
telemt_handshake_timeouts_total 1093
telemt_upstream_connect_attempt_total 8343
telemt_upstream_connect_success_total 8291
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 8343
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3448
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4707
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 136
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 152
telemt_me_reconnect_attempts_total 9241
telemt_me_reconnect_success_total 6657
telemt_me_reader_eof_total 7095
telemt_me_idle_close_by_peer_total 7095
telemt_me_route_drop_no_conn_total 32914
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 57462
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
telemt_me_writer_removed_unexpected_total 6824
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 6652
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 167
telemt_user_connections_total{user="hello"} 57383
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 1441159536 (1.34 GB)
telemt_user_octets_to_client{user="hello"} 26613416976 (24.79 GB)
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 32046.0 (8h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69695
telemt_connections_bad_total 395
telemt_handshake_timeouts_total 1918
telemt_upstream_connect_attempt_total 10451
telemt_upstream_connect_success_total 10345
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 10451
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4771
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5561
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_timeout_total 276
telemt_me_reconnect_attempts_total 106262
telemt_me_reconnect_success_total 8396
telemt_me_reader_eof_total 8981
telemt_me_idle_close_by_peer_total 8981
telemt_me_route_drop_no_conn_total 25751
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 63911
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
telemt_me_writer_removed_unexpected_total 8684
telemt_me_refill_failed_total 3169
telemt_me_writer_restored_same_endpoint_total 8350
telemt_me_writer_restored_fallback_total 46
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 288
telemt_user_connections_total{user="hello"} 63974
telemt_user_connections_current{user="hello"} 89
telemt_user_octets_from_client{user="hello"} 3988024921 (3.71 GB)
telemt_user_octets_to_client{user="hello"} 51066601098 (47.56 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 32050.9 (8h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87377
telemt_connections_bad_total 215
telemt_handshake_timeouts_total 623
telemt_upstream_connect_attempt_total 7825
telemt_upstream_connect_success_total 7778
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 7825
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3610
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4135
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 214
telemt_me_reconnect_attempts_total 6011
telemt_me_reconnect_success_total 5981
telemt_me_reader_eof_total 6317
telemt_me_idle_close_by_peer_total 6317
telemt_me_route_drop_no_conn_total 38222
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 82869
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
telemt_me_writer_removed_unexpected_total 6048
telemt_me_writer_restored_same_endpoint_total 5979
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 82912
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 1414966604 (1.32 GB)
telemt_user_octets_to_client{user="hello"} 30287225670 (28.21 GB)
telemt_user_msgs_from_client{user="hello"} 473
telemt_user_msgs_to_client{user="hello"} 2783
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 32044.1 (8h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66596
telemt_connections_bad_total 6229
telemt_handshake_timeouts_total 3390
telemt_upstream_connect_attempt_total 7939
telemt_upstream_connect_success_total 7846
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 7939
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3544
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4250
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 240
telemt_me_reconnect_attempts_total 12750
telemt_me_reconnect_success_total 6209
telemt_me_reader_eof_total 6702
telemt_me_idle_close_by_peer_total 6702
telemt_me_route_drop_no_conn_total 21338
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 53707
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
telemt_me_writer_removed_unexpected_total 6471
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 6205
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 262
telemt_user_connections_total{user="hello"} 53692
telemt_user_connections_current{user="hello"} 93
telemt_user_octets_from_client{user="hello"} 1420696488 (1.32 GB)
telemt_user_octets_to_client{user="hello"} 32392801832 (30.17 GB)
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 32043.7 (8h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 223261
telemt_connections_bad_total 7770
telemt_handshake_timeouts_total 2760
telemt_upstream_connect_attempt_total 6423
telemt_upstream_connect_success_total 6310
telemt_upstream_connect_fail_total 113
telemt_upstream_connect_attempts_per_request{bucket="1"} 6423
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3071
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3234
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 113
telemt_me_keepalive_timeout_total 267
telemt_me_reconnect_attempts_total 9689
telemt_me_reconnect_success_total 4679
telemt_me_reader_eof_total 5060
telemt_me_idle_close_by_peer_total 5060
telemt_me_route_drop_no_conn_total 124861
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 206231
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
telemt_me_writer_removed_unexpected_total 4893
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 4675
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 214
telemt_user_connections_total{user="hello"} 202714
telemt_user_connections_current{user="hello"} 302
telemt_user_octets_from_client{user="hello"} 6357161944 (5.92 GB)
telemt_user_octets_to_client{user="hello"} 113771329452 (105.96 GB)
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 35
```