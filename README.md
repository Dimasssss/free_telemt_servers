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

# Server Metrics 2026-03-15 18:02:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 71263.1 (19h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 334130
telemt_connections_bad_total 4186
telemt_handshake_timeouts_total 10477
telemt_upstream_connect_attempt_total 17335
telemt_upstream_connect_success_total 17248
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 17335
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7637
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9577
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 17067
telemt_me_reconnect_success_total 13670
telemt_me_reader_eof_total 14561
telemt_me_idle_close_by_peer_total 14561
telemt_me_route_drop_no_conn_total 462357
telemt_me_route_drop_channel_closed_total 76
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 367545
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1855
telemt_desync_full_logged_total 738
telemt_desync_suppressed_total 1117
telemt_desync_frames_bucket_total{bucket="1_2"} 347
telemt_desync_frames_bucket_total{bucket="3_10"} 727
telemt_desync_frames_bucket_total{bucket="gt_10"} 781
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 13922
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 13636
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 252
telemt_user_connections_total{user="hello"} 306645
telemt_user_connections_current{user="hello"} 348
telemt_user_octets_from_client{user="hello"} 6244389972 (5.82 GB)
telemt_user_octets_to_client{user="hello"} 241414797360 (224.84 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 71270.8 (19h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 133648
telemt_connections_bad_total 2834
telemt_handshake_timeouts_total 12130
telemt_upstream_connect_attempt_total 19374
telemt_upstream_connect_success_total 19374
telemt_upstream_connect_attempts_per_request{bucket="1"} 19374
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8281
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10785
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 308
telemt_me_keepalive_timeout_total 44
telemt_me_reconnect_attempts_total 18120
telemt_me_reconnect_success_total 15754
telemt_me_reader_eof_total 16845
telemt_me_idle_close_by_peer_total 16844
telemt_me_route_drop_no_conn_total 55290
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 113177
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3
telemt_desync_full_logged_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 16032
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 15738
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 278
telemt_user_connections_total{user="hello"} 113157
telemt_user_connections_current{user="hello"} 198
telemt_user_octets_from_client{user="hello"} 2127092852 (1.98 GB)
telemt_user_octets_to_client{user="hello"} 56209791956 (52.35 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 71261.9 (19h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 137866
telemt_connections_bad_total 1697
telemt_handshake_timeouts_total 3284
telemt_upstream_connect_attempt_total 20888
telemt_upstream_connect_success_total 20880
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 20888
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9061
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11783
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 24604
telemt_me_reconnect_success_total 17246
telemt_me_reader_eof_total 18513
telemt_me_idle_close_by_peer_total 18513
telemt_me_route_drop_no_conn_total 53954
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 121151
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 59
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 17641
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 17238
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 395
telemt_user_connections_total{user="hello"} 121043
telemt_user_connections_current{user="hello"} 185
telemt_user_octets_from_client{user="hello"} 10716572240 (9.98 GB)
telemt_user_octets_to_client{user="hello"} 68161974612 (63.48 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 71261.8 (19h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 188592
telemt_connections_bad_total 940
telemt_handshake_timeouts_total 1266
telemt_upstream_connect_attempt_total 16912
telemt_upstream_connect_success_total 16900
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 16912
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8095
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8736
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 13406
telemt_me_reconnect_success_total 13322
telemt_me_reader_eof_total 14181
telemt_me_idle_close_by_peer_total 14181
telemt_me_route_drop_no_conn_total 71684
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 173818
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 613
telemt_desync_full_logged_total 226
telemt_desync_suppressed_total 387
telemt_desync_frames_bucket_total{bucket="1_2"} 129
telemt_desync_frames_bucket_total{bucket="3_10"} 283
telemt_desync_frames_bucket_total{bucket="gt_10"} 201
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 13485
telemt_me_writer_restored_same_endpoint_total 13311
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 163
telemt_user_connections_total{user="hello"} 173730
telemt_user_connections_current{user="hello"} 231
telemt_user_octets_from_client{user="hello"} 3216630448 (3.00 GB)
telemt_user_octets_to_client{user="hello"} 78853252916 (73.44 GB)
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 46333.2 (12h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114208
telemt_connections_bad_total 23813
telemt_handshake_timeouts_total 2458
telemt_upstream_connect_attempt_total 13862
telemt_upstream_connect_success_total 13782
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 13862
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6319
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 105720
telemt_me_reconnect_success_total 11276
telemt_me_reader_eof_total 11840
telemt_me_idle_close_by_peer_total 11840
telemt_me_route_drop_no_conn_total 39214
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 84773
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 242
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 190
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 89
telemt_desync_frames_bucket_total{bucket="gt_10"} 110
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 11342
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 11172
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 84906
telemt_user_connections_current{user="hello"} 133
telemt_user_octets_from_client{user="hello"} 1444034785 (1.34 GB)
telemt_user_octets_to_client{user="hello"} 33286029639 (31.00 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 71261.6 (19h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 477511
telemt_connections_bad_total 57650
telemt_handshake_timeouts_total 3901
telemt_upstream_connect_attempt_total 15411
telemt_upstream_connect_success_total 15320
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 15411
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7418
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7872
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 13019
telemt_me_reconnect_success_total 11714
telemt_me_reader_eof_total 12446
telemt_me_idle_close_by_peer_total 12446
telemt_me_route_drop_no_conn_total 305357
telemt_me_route_drop_channel_closed_total 75
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 438829
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 317
telemt_desync_full_logged_total 86
telemt_desync_suppressed_total 231
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 11879
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 11687
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 398452
telemt_user_connections_current{user="hello"} 674
telemt_user_octets_from_client{user="hello"} 10436403664 (9.72 GB)
telemt_user_octets_to_client{user="hello"} 214703083424 (199.96 GB)
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 74
```