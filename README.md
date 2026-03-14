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

# Server Metrics 2026-03-14 07:53:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 174017.8 (48h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 667664
telemt_connections_bad_total 32402
telemt_handshake_timeouts_total 13151
telemt_upstream_connect_attempt_total 44270
telemt_upstream_connect_success_total 44047
telemt_upstream_connect_fail_total 223
telemt_upstream_connect_attempts_per_request{bucket="1"} 44270
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20155
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23740
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 223
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5698
telemt_me_reconnect_attempts_total 39682
telemt_me_reconnect_success_total 34988
telemt_me_reader_eof_total 37419
telemt_me_idle_close_by_peer_total 37418
telemt_me_route_drop_no_conn_total 220830
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 568976
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2184
telemt_desync_full_logged_total 743
telemt_desync_suppressed_total 1441
telemt_desync_frames_bucket_total{bucket="1_2"} 471
telemt_desync_frames_bucket_total{bucket="3_10"} 805
telemt_desync_frames_bucket_total{bucket="gt_10"} 908
telemt_pool_swap_total 161
telemt_me_writer_removed_unexpected_total 35509
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 34968
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 521
telemt_user_connections_total{user="hello"} 568859
telemt_user_connections_current{user="hello"} 339
telemt_user_octets_from_client{user="hello"} 16591679426 (15.45 GB)
telemt_user_octets_to_client{user="hello"} 272493673972 (253.78 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 173911.3 (48h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 336097
telemt_connections_bad_total 2328
telemt_handshake_timeouts_total 2634
telemt_upstream_connect_attempt_total 151416
telemt_upstream_connect_success_total 150128
telemt_upstream_connect_fail_total 1288
telemt_upstream_connect_attempts_per_request{bucket="1"} 151416
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 110310
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37391
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2427
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1288
telemt_me_keepalive_timeout_total 4034
telemt_me_reconnect_attempts_total 178740
telemt_me_reconnect_success_total 38145
telemt_me_reader_eof_total 43584
telemt_me_idle_close_by_peer_total 43584
telemt_me_route_drop_no_conn_total 112126
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 214981
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 43
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
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 42900
telemt_me_refill_failed_total 4387
telemt_me_writer_restored_same_endpoint_total 38128
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4755
telemt_user_connections_total{user="hello"} 318087
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 3295560071 (3.07 GB)
telemt_user_octets_to_client{user="hello"} 103623620743 (96.51 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 173874.8 (48h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 393106
telemt_connections_bad_total 3181
telemt_handshake_timeouts_total 35221
telemt_upstream_connect_attempt_total 45922
telemt_upstream_connect_success_total 45913
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 45922
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20997
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24848
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3503
telemt_me_reconnect_attempts_total 38484
telemt_me_reconnect_success_total 37196
telemt_me_reader_eof_total 40002
telemt_me_idle_close_by_peer_total 40002
telemt_me_route_drop_no_conn_total 142268
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 340949
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
telemt_pool_swap_total 165
telemt_me_writer_removed_unexpected_total 37646
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 37175
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 450
telemt_user_connections_total{user="hello"} 340720
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 13602902572 (12.67 GB)
telemt_user_octets_to_client{user="hello"} 138900234196 (129.36 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 173850.6 (48h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 495312
telemt_connections_bad_total 16266
telemt_handshake_timeouts_total 4546
telemt_upstream_connect_attempt_total 76429
telemt_upstream_connect_success_total 65817
telemt_upstream_connect_fail_total 10612
telemt_upstream_connect_attempts_per_request{bucket="1"} 76429
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38689
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26776
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 343
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10612
telemt_me_keepalive_timeout_total 5453
telemt_me_reconnect_attempts_total 144430
telemt_me_reconnect_success_total 38111
telemt_me_reader_eof_total 42661
telemt_me_idle_close_by_peer_total 42653
telemt_me_route_drop_no_conn_total 179489
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 422306
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1810
telemt_desync_full_logged_total 541
telemt_desync_suppressed_total 1269
telemt_desync_frames_bucket_total{bucket="1_2"} 430
telemt_desync_frames_bucket_total{bucket="3_10"} 688
telemt_desync_frames_bucket_total{bucket="gt_10"} 692
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 41870
telemt_me_refill_failed_total 3315
telemt_me_writer_restored_same_endpoint_total 38101
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3759
telemt_user_connections_total{user="hello"} 441182
telemt_user_connections_current{user="hello"} 195
telemt_user_octets_from_client{user="hello"} 9485773531 (8.83 GB)
telemt_user_octets_to_client{user="hello"} 180572083544 (168.17 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 124022.1 (34h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 202699
telemt_connections_bad_total 30217
telemt_handshake_timeouts_total 1763
telemt_upstream_connect_attempt_total 43484
telemt_upstream_connect_success_total 43066
telemt_upstream_connect_fail_total 417
telemt_upstream_connect_attempts_per_request{bucket="1"} 43483
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21549
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21375
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 142
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 417
telemt_me_keepalive_timeout_total 2529
telemt_me_reconnect_attempts_total 45456
telemt_me_reconnect_success_total 32021
telemt_me_reader_eof_total 34286
telemt_me_idle_close_by_peer_total 34286
telemt_me_route_drop_no_conn_total 60565
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 160262
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 701
telemt_desync_full_logged_total 171
telemt_desync_suppressed_total 530
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 335
telemt_desync_frames_bucket_total{bucket="gt_10"} 252
telemt_pool_swap_total 96
telemt_me_writer_removed_unexpected_total 32739
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 32003
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 718
telemt_user_connections_total{user="hello"} 165022
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 2439179797 (2.27 GB)
telemt_user_octets_to_client{user="hello"} 78244572631 (72.87 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 173806.8 (48h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 997021
telemt_connections_bad_total 36112
telemt_handshake_timeouts_total 26196
telemt_upstream_connect_attempt_total 36018
telemt_upstream_connect_success_total 35827
telemt_upstream_connect_fail_total 191
telemt_upstream_connect_attempts_per_request{bucket="1"} 36018
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16855
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18931
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 191
telemt_me_keepalive_timeout_total 4724
telemt_me_reconnect_attempts_total 31894
telemt_me_reconnect_success_total 27213
telemt_me_reader_eof_total 29212
telemt_me_idle_close_by_peer_total 29209
telemt_me_route_drop_no_conn_total 468940
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 923930
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 770
telemt_desync_full_logged_total 254
telemt_desync_suppressed_total 516
telemt_desync_frames_bucket_total{bucket="1_2"} 257
telemt_desync_frames_bucket_total{bucket="3_10"} 253
telemt_desync_frames_bucket_total{bucket="gt_10"} 260
telemt_pool_swap_total 166
telemt_me_writer_removed_unexpected_total 27705
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 27206
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 492
telemt_user_connections_total{user="hello"} 896572
telemt_user_connections_current{user="hello"} 399
telemt_user_octets_from_client{user="hello"} 15281198524 (14.23 GB)
telemt_user_octets_to_client{user="hello"} 449278548924 (418.42 GB)
telemt_user_unique_ips_current{user="hello"} 168
telemt_user_unique_ips_recent_window{user="hello"} 61
```