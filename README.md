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

# Server Metrics 2026-03-15 21:16:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 82898.6 (23h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 384004
telemt_connections_bad_total 5070
telemt_handshake_timeouts_total 13798
telemt_upstream_connect_attempt_total 19798
telemt_upstream_connect_success_total 19699
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 19798
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8715
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10937
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 18959
telemt_me_reconnect_success_total 15555
telemt_me_reader_eof_total 16580
telemt_me_idle_close_by_peer_total 16580
telemt_me_route_drop_no_conn_total 482189
telemt_me_route_drop_channel_closed_total 78
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 411669
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2025
telemt_desync_full_logged_total 795
telemt_desync_suppressed_total 1230
telemt_desync_frames_bucket_total{bucket="1_2"} 381
telemt_desync_frames_bucket_total{bucket="3_10"} 790
telemt_desync_frames_bucket_total{bucket="gt_10"} 854
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 15832
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 15521
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 277
telemt_user_connections_total{user="hello"} 350731
telemt_user_connections_current{user="hello"} 261
telemt_user_octets_from_client{user="hello"} 7840400456 (7.30 GB)
telemt_user_octets_to_client{user="hello"} 265098307424 (246.89 GB)
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 82904.8 (23h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 159466
telemt_connections_bad_total 2870
telemt_handshake_timeouts_total 13963
telemt_upstream_connect_attempt_total 22677
telemt_upstream_connect_success_total 22602
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 22677
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9832
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12163
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 607
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1305
telemt_me_reconnect_attempts_total 24928
telemt_me_reconnect_success_total 18043
telemt_me_reader_eof_total 19295
telemt_me_idle_close_by_peer_total 19294
telemt_me_route_drop_no_conn_total 65792
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 136021
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 24
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 18534
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 18027
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 491
telemt_user_connections_total{user="hello"} 136291
telemt_user_connections_current{user="hello"} 178
telemt_user_octets_from_client{user="hello"} 2592431661 (2.41 GB)
telemt_user_octets_to_client{user="hello"} 70790981244 (65.93 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 82897.8 (23h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 158543
telemt_connections_bad_total 1740
telemt_handshake_timeouts_total 3414
telemt_upstream_connect_attempt_total 23763
telemt_upstream_connect_success_total 23755
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 23763
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10311
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13397
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 26919
telemt_me_reconnect_success_total 19552
telemt_me_reader_eof_total 20997
telemt_me_idle_close_by_peer_total 20996
telemt_me_route_drop_no_conn_total 63178
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 140955
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 60
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 19971
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 19544
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 419
telemt_user_connections_total{user="hello"} 140837
telemt_user_connections_current{user="hello"} 158
telemt_user_octets_from_client{user="hello"} 10960512764 (10.21 GB)
telemt_user_octets_to_client{user="hello"} 84156747828 (78.38 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 82897.4 (23h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 230080
telemt_connections_bad_total 1188
telemt_handshake_timeouts_total 1586
telemt_upstream_connect_attempt_total 19357
telemt_upstream_connect_success_total 19339
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 19357
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9274
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9980
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 15288
telemt_me_reconnect_success_total 15195
telemt_me_reader_eof_total 16185
telemt_me_idle_close_by_peer_total 16185
telemt_me_route_drop_no_conn_total 84066
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 211863
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 786
telemt_desync_full_logged_total 277
telemt_desync_suppressed_total 509
telemt_desync_frames_bucket_total{bucket="1_2"} 157
telemt_desync_frames_bucket_total{bucket="3_10"} 344
telemt_desync_frames_bucket_total{bucket="gt_10"} 285
telemt_pool_swap_total 78
telemt_me_writer_removed_unexpected_total 15378
telemt_me_writer_restored_same_endpoint_total 15184
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 183
telemt_user_connections_total{user="hello"} 211780
telemt_user_connections_current{user="hello"} 211
telemt_user_octets_from_client{user="hello"} 3983350456 (3.71 GB)
telemt_user_octets_to_client{user="hello"} 97799374884 (91.08 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 57968.7 (16h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 141017
telemt_connections_bad_total 27061
telemt_handshake_timeouts_total 2541
telemt_upstream_connect_attempt_total 16834
telemt_upstream_connect_success_total 16732
telemt_upstream_connect_fail_total 102
telemt_upstream_connect_attempts_per_request{bucket="1"} 16834
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7592
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9037
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 103
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 102
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 108110
telemt_me_reconnect_success_total 13655
telemt_me_reader_eof_total 14389
telemt_me_idle_close_by_peer_total 14389
telemt_me_route_drop_no_conn_total 46662
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 107521
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 337
telemt_desync_full_logged_total 78
telemt_desync_suppressed_total 259
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 127
telemt_desync_frames_bucket_total{bucket="gt_10"} 159
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 13749
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 13551
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 107649
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 1674836033 (1.56 GB)
telemt_user_octets_to_client{user="hello"} 41078110779 (38.26 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 82896.6 (23h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 557823
telemt_connections_bad_total 58527
telemt_handshake_timeouts_total 4365
telemt_upstream_connect_attempt_total 17568
telemt_upstream_connect_success_total 17466
telemt_upstream_connect_fail_total 102
telemt_upstream_connect_attempts_per_request{bucket="1"} 17568
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8373
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9053
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 102
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 14608
telemt_me_reconnect_success_total 13296
telemt_me_reader_eof_total 14136
telemt_me_idle_close_by_peer_total 14136
telemt_me_route_drop_no_conn_total 411868
telemt_me_route_drop_channel_closed_total 95
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 552399
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 323
telemt_desync_full_logged_total 90
telemt_desync_suppressed_total 233
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 13482
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 13269
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 186
telemt_user_connections_total{user="hello"} 474077
telemt_user_connections_current{user="hello"} 402
telemt_user_octets_from_client{user="hello"} 11853314656 (11.04 GB)
telemt_user_octets_to_client{user="hello"} 278341304776 (259.23 GB)
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 43
```