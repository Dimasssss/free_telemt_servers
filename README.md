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

# Server Metrics 2026-03-18 14:46:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 21950.5 (6h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 818233
telemt_connections_bad_total 53295
telemt_handshake_timeouts_total 22599
telemt_upstream_connect_attempt_total 67141
telemt_upstream_connect_success_total 66172
telemt_upstream_connect_fail_total 969
telemt_upstream_connect_attempts_per_request{bucket="1"} 67141
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60979
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4610
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 969
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 518586
telemt_me_reconnect_success_total 3065
telemt_me_reader_eof_total 3359
telemt_me_idle_close_by_peer_total 3357
telemt_me_route_drop_no_conn_total 451786
telemt_me_route_drop_channel_closed_total 175
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 629558
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2825
telemt_desync_full_logged_total 971
telemt_desync_suppressed_total 1854
telemt_desync_frames_bucket_total{bucket="1_2"} 799
telemt_desync_frames_bucket_total{bucket="3_10"} 960
telemt_desync_frames_bucket_total{bucket="gt_10"} 1066
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 3363
telemt_me_refill_failed_total 16792
telemt_me_writer_restored_same_endpoint_total 2959
telemt_me_writer_restored_fallback_total 106
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 298
telemt_user_connections_total{user="hello"} 687648
telemt_user_connections_current{user="hello"} 1634
telemt_user_octets_from_client{user="hello"} 10226996164 (9.52 GB)
telemt_user_octets_to_client{user="hello"} 180620591857 (168.22 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 551
telemt_user_unique_ips_recent_window{user="hello"} 235
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 2518.5 (0h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 267580
telemt_connections_bad_total 14912
telemt_connections_current 3972
telemt_connections_me_current 3972
telemt_handshake_timeouts_total 5540
telemt_upstream_connect_attempt_total 417
telemt_upstream_connect_success_total 414
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 417
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 257
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 156
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 259
telemt_me_reconnect_success_total 255
telemt_me_reader_eof_total 156
telemt_me_idle_close_by_peer_total 155
telemt_me_route_drop_no_conn_total 146010
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 234322
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 724
telemt_desync_full_logged_total 206
telemt_desync_suppressed_total 518
telemt_desync_frames_bucket_total{bucket="1_2"} 177
telemt_desync_frames_bucket_total{bucket="3_10"} 282
telemt_desync_frames_bucket_total{bucket="gt_10"} 265
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 173
telemt_me_writer_restored_same_endpoint_total 253
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 233604
telemt_user_connections_current{user="hello"} 3972
telemt_user_octets_from_client{user="hello"} 2431602728 (2.26 GB)
telemt_user_octets_to_client{user="hello"} 72721710524 (67.73 GB)
telemt_user_unique_ips_current{user="hello"} 1209
telemt_user_unique_ips_recent_window{user="hello"} 572
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 2447.0 (0h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 175587
telemt_connections_bad_total 8302
telemt_connections_current 3123
telemt_connections_me_current 3123
telemt_handshake_timeouts_total 3719
telemt_upstream_connect_attempt_total 330
telemt_upstream_connect_success_total 327
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 330
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 180
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 172
telemt_me_reconnect_success_total 171
telemt_me_reader_eof_total 158
telemt_me_idle_close_by_peer_total 158
telemt_me_route_drop_no_conn_total 61008
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 152700
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 490
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 347
telemt_desync_frames_bucket_total{bucket="1_2"} 84
telemt_desync_frames_bucket_total{bucket="3_10"} 172
telemt_desync_frames_bucket_total{bucket="gt_10"} 234
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 175
telemt_me_writer_restored_same_endpoint_total 154
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 152680
telemt_user_connections_current{user="hello"} 3123
telemt_user_octets_from_client{user="hello"} 3268292476 (3.04 GB)
telemt_user_octets_to_client{user="hello"} 60470416700 (56.32 GB)
telemt_user_unique_ips_current{user="hello"} 952
telemt_user_unique_ips_recent_window{user="hello"} 543
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 3161.2 (0h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 283756
telemt_connections_bad_total 1086
telemt_connections_current 2855
telemt_connections_me_current 2855
telemt_handshake_timeouts_total 5649
telemt_upstream_connect_attempt_total 567
telemt_upstream_connect_success_total 565
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 567
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 275
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 286
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 363
telemt_me_reconnect_success_total 359
telemt_me_reader_eof_total 322
telemt_me_idle_close_by_peer_total 321
telemt_me_route_drop_no_conn_total 353722
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 251967
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 755
telemt_desync_full_logged_total 217
telemt_desync_suppressed_total 538
telemt_desync_frames_bucket_total{bucket="1_2"} 161
telemt_desync_frames_bucket_total{bucket="3_10"} 334
telemt_desync_frames_bucket_total{bucket="gt_10"} 260
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 335
telemt_me_writer_restored_same_endpoint_total 348
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_user_connections_total{user="hello"} 251910
telemt_user_connections_current{user="hello"} 2855
telemt_user_octets_from_client{user="hello"} 1730504068 (1.61 GB)
telemt_user_octets_to_client{user="hello"} 45653106724 (42.52 GB)
telemt_user_unique_ips_current{user="hello"} 841
telemt_user_unique_ips_recent_window{user="hello"} 404
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 21821.3 (6h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1795134
telemt_connections_bad_total 143417
telemt_handshake_timeouts_total 28566
telemt_upstream_connect_attempt_total 15377
telemt_upstream_connect_success_total 15349
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 15377
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12509
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2036
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 804
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 70
telemt_me_reconnect_attempts_total 2986993
telemt_me_reconnect_success_total 2554
telemt_me_reader_eof_total 2672
telemt_me_idle_close_by_peer_total 2672
telemt_me_route_drop_no_conn_total 1874984
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1492909
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4231
telemt_desync_full_logged_total 1476
telemt_desync_suppressed_total 2755
telemt_desync_frames_bucket_total{bucket="1_2"} 687
telemt_desync_frames_bucket_total{bucket="3_10"} 1652
telemt_desync_frames_bucket_total{bucket="gt_10"} 1892
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 2626
telemt_me_refill_failed_total 107230
telemt_me_writer_restored_same_endpoint_total 2439
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 1494727
telemt_user_connections_current{user="hello"} 2981
telemt_user_octets_from_client{user="hello"} 22466888611 (20.92 GB)
telemt_user_octets_to_client{user="hello"} 497577677541 (463.41 GB)
telemt_user_msgs_from_client{user="hello"} 89703
telemt_user_msgs_to_client{user="hello"} 269409
telemt_user_unique_ips_current{user="hello"} 985
telemt_user_unique_ips_recent_window{user="hello"} 420
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 2611.5 (0h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64163
telemt_connections_bad_total 4296
telemt_connections_current 880
telemt_connections_me_current 880
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 683
telemt_upstream_connect_attempt_total 4532
telemt_upstream_connect_success_total 4527
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 4532
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2687
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1812
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 22
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 330001
telemt_me_reconnect_success_total 547
telemt_me_reader_eof_total 444
telemt_me_idle_close_by_peer_total 444
telemt_me_route_drop_no_conn_total 38661
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 52530
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 115
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 78
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 43
telemt_desync_frames_bucket_total{bucket="gt_10"} 45
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 461
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 536
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 56303
telemt_user_connections_current{user="hello"} 880
telemt_user_octets_from_client{user="hello"} 1014863877 (967.85 MB)
telemt_user_octets_to_client{user="hello"} 8651292097 (8.06 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 313
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 1680.4 (0h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 133637
telemt_connections_bad_total 4880
telemt_connections_current 2636
telemt_connections_me_current 2636
telemt_handshake_timeouts_total 1192
telemt_upstream_connect_attempt_total 369
telemt_upstream_connect_success_total 369
telemt_upstream_connect_attempts_per_request{bucket="1"} 369
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 224
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 144
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 14542
telemt_me_reconnect_success_total 254
telemt_me_reader_eof_total 139
telemt_me_idle_close_by_peer_total 139
telemt_me_route_drop_no_conn_total 143348
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 118663
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 276
telemt_desync_full_logged_total 92
telemt_desync_suppressed_total 184
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 78
telemt_desync_frames_bucket_total{bucket="gt_10"} 124
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 161
telemt_me_refill_failed_total 703
telemt_me_writer_restored_same_endpoint_total 193
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 118678
telemt_user_connections_current{user="hello"} 2636
telemt_user_octets_from_client{user="hello"} 1213373324 (1.13 GB)
telemt_user_octets_to_client{user="hello"} 29014531772 (27.02 GB)
telemt_user_unique_ips_current{user="hello"} 784
telemt_user_unique_ips_recent_window{user="hello"} 337
```