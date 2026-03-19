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

# Server Metrics 2026-03-19 08:26:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 38277.8 (10h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 721008
telemt_connections_bad_total 74005
telemt_connections_current 1581
telemt_connections_me_current 1581
telemt_handshake_timeouts_total 25911
telemt_upstream_connect_attempt_total 7257
telemt_upstream_connect_success_total 7127
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 7257
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3463
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3661
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 68
telemt_me_reconnect_attempts_total 6360
telemt_me_reconnect_success_total 5206
telemt_me_reader_eof_total 5523
telemt_me_idle_close_by_peer_total 5522
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 206065
telemt_me_route_drop_channel_closed_total 83
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 551316
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3570
telemt_desync_full_logged_total 1041
telemt_desync_suppressed_total 2529
telemt_desync_frames_bucket_total{bucket="1_2"} 1233
telemt_desync_frames_bucket_total{bucket="3_10"} 1329
telemt_desync_frames_bucket_total{bucket="gt_10"} 1008
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 5302
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 5189
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 548333
telemt_user_connections_current{user="hello"} 1581
telemt_user_octets_from_client{user="hello"} 7859887904 (7.32 GB)
telemt_user_octets_to_client{user="hello"} 183474820504 (170.87 GB)
telemt_user_unique_ips_current{user="hello"} 551
telemt_user_unique_ips_recent_window{user="hello"} 266
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 38281.6 (10h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1756159
telemt_connections_bad_total 99525
telemt_connections_current 4186
telemt_connections_me_current 4186
telemt_handshake_timeouts_total 40832
telemt_upstream_connect_attempt_total 7229
telemt_upstream_connect_success_total 7094
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 7229
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3519
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3556
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 30
telemt_me_reconnect_attempts_total 6316
telemt_me_reconnect_success_total 5159
telemt_me_reader_eof_total 5470
telemt_me_idle_close_by_peer_total 5470
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 772423
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1452281
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6470
telemt_desync_full_logged_total 2170
telemt_desync_suppressed_total 4300
telemt_desync_frames_bucket_total{bucket="1_2"} 1171
telemt_desync_frames_bucket_total{bucket="3_10"} 2453
telemt_desync_frames_bucket_total{bucket="gt_10"} 2846
telemt_pool_swap_total 31
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 5287
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 5137
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 128
telemt_user_connections_total{user="hello"} 1452091
telemt_user_connections_current{user="hello"} 4186
telemt_user_octets_from_client{user="hello"} 24753861712 (23.05 GB)
telemt_user_octets_to_client{user="hello"} 555800964388 (517.63 GB)
telemt_user_unique_ips_current{user="hello"} 1432
telemt_user_unique_ips_recent_window{user="hello"} 615
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 38279.2 (10h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1489394
telemt_connections_bad_total 193881
telemt_connections_current 3088
telemt_connections_me_current 3088
telemt_handshake_timeouts_total 37125
telemt_upstream_connect_attempt_total 6826
telemt_upstream_connect_success_total 6826
telemt_upstream_connect_attempts_per_request{bucket="1"} 6826
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3548
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3266
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 4920
telemt_me_reconnect_success_total 4892
telemt_me_reader_eof_total 5186
telemt_me_idle_close_by_peer_total 5186
telemt_me_route_drop_no_conn_total 673080
telemt_me_route_drop_channel_closed_total 50
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1141340
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5368
telemt_desync_full_logged_total 1660
telemt_desync_suppressed_total 3708
telemt_desync_frames_bucket_total{bucket="1_2"} 1156
telemt_desync_frames_bucket_total{bucket="3_10"} 1928
telemt_desync_frames_bucket_total{bucket="gt_10"} 2284
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 4982
telemt_me_writer_restored_same_endpoint_total 4876
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 1140927
telemt_user_connections_current{user="hello"} 3088
telemt_user_octets_from_client{user="hello"} 19020145708 (17.71 GB)
telemt_user_octets_to_client{user="hello"} 563570250060 (524.87 GB)
telemt_user_unique_ips_current{user="hello"} 1068
telemt_user_unique_ips_recent_window{user="hello"} 488
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 38332.3 (10h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1561882
telemt_connections_bad_total 94613
telemt_connections_current 2941
telemt_connections_me_current 2941
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 39436
telemt_upstream_connect_attempt_total 15033
telemt_upstream_connect_success_total 14937
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 15033
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10763
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4026
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7237
telemt_me_reconnect_success_total 4849
telemt_me_reader_eof_total 5155
telemt_me_idle_close_by_peer_total 5154
telemt_me_route_drop_no_conn_total 688495
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1112117
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4019
telemt_desync_full_logged_total 1375
telemt_desync_suppressed_total 2644
telemt_desync_frames_bucket_total{bucket="1_2"} 789
telemt_desync_frames_bucket_total{bucket="3_10"} 1583
telemt_desync_frames_bucket_total{bucket="gt_10"} 1647
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 5102
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 4825
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 253
telemt_user_connections_total{user="hello"} 1118962
telemt_user_connections_current{user="hello"} 2941
telemt_user_octets_from_client{user="hello"} 14416090628 (13.43 GB)
telemt_user_octets_to_client{user="hello"} 352674431398 (328.45 GB)
telemt_user_msgs_from_client{user="hello"} 28643
telemt_user_msgs_to_client{user="hello"} 76631
telemt_user_unique_ips_current{user="hello"} 995
telemt_user_unique_ips_recent_window{user="hello"} 457
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 38275.4 (10h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1833749
telemt_connections_bad_total 476089
telemt_connections_current 3455
telemt_connections_me_current 3455
telemt_handshake_timeouts_total 38351
telemt_upstream_connect_attempt_total 6594
telemt_upstream_connect_success_total 6549
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 6594
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3314
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3214
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 4656
telemt_me_reconnect_success_total 4623
telemt_me_reader_eof_total 4906
telemt_me_idle_close_by_peer_total 4906
telemt_me_route_drop_no_conn_total 477748
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1130147
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5527
telemt_desync_full_logged_total 1717
telemt_desync_suppressed_total 3810
telemt_desync_frames_bucket_total{bucket="1_2"} 1129
telemt_desync_frames_bucket_total{bucket="3_10"} 2481
telemt_desync_frames_bucket_total{bucket="gt_10"} 1917
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 4687
telemt_me_writer_restored_same_endpoint_total 4599
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 1129775
telemt_user_connections_current{user="hello"} 3455
telemt_user_octets_from_client{user="hello"} 22732286288 (21.17 GB)
telemt_user_octets_to_client{user="hello"} 532048735652 (495.51 GB)
telemt_user_unique_ips_current{user="hello"} 1171
telemt_user_unique_ips_recent_window{user="hello"} 550
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 38287.2 (10h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 314148
telemt_connections_bad_total 14737
telemt_connections_current 846
telemt_connections_me_current 846
telemt_handshake_timeouts_total 2794
telemt_upstream_connect_attempt_total 9803
telemt_upstream_connect_success_total 9549
telemt_upstream_connect_fail_total 254
telemt_upstream_connect_attempts_per_request{bucket="1"} 9803
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4709
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4839
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 254
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 12999
telemt_me_reconnect_success_total 7620
telemt_me_reader_eof_total 8092
telemt_me_idle_close_by_peer_total 8092
telemt_me_route_drop_no_conn_total 144837
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 280696
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 405
telemt_desync_full_logged_total 139
telemt_desync_suppressed_total 266
telemt_desync_frames_bucket_total{bucket="1_2"} 119
telemt_desync_frames_bucket_total{bucket="3_10"} 166
telemt_desync_frames_bucket_total{bucket="gt_10"} 120
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 7841
telemt_me_refill_failed_total 167
telemt_me_writer_restored_same_endpoint_total 7590
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 221
telemt_user_connections_total{user="hello"} 280658
telemt_user_connections_current{user="hello"} 846
telemt_user_octets_from_client{user="hello"} 4170472728 (3.88 GB)
telemt_user_octets_to_client{user="hello"} 125676216380 (117.05 GB)
telemt_user_unique_ips_current{user="hello"} 324
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 38277.9 (10h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1197446
telemt_connections_bad_total 97974
telemt_connections_current 3108
telemt_connections_me_current 3108
telemt_handshake_timeouts_total 52713
telemt_upstream_connect_attempt_total 7742
telemt_upstream_connect_success_total 7741
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 7742
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4116
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3622
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 42
telemt_me_reconnect_attempts_total 7151
telemt_me_reconnect_success_total 5809
telemt_me_reader_eof_total 6166
telemt_me_idle_close_by_peer_total 6165
telemt_me_route_drop_no_conn_total 476410
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1000849
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5941
telemt_desync_full_logged_total 1951
telemt_desync_suppressed_total 3990
telemt_desync_frames_bucket_total{bucket="1_2"} 1139
telemt_desync_frames_bucket_total{bucket="3_10"} 2232
telemt_desync_frames_bucket_total{bucket="gt_10"} 2570
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 5916
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 5794
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 999814
telemt_user_connections_current{user="hello"} 3108
telemt_user_octets_from_client{user="hello"} 14004707272 (13.04 GB)
telemt_user_octets_to_client{user="hello"} 510467181176 (475.41 GB)
telemt_user_unique_ips_current{user="hello"} 986
telemt_user_unique_ips_recent_window{user="hello"} 432
```