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

# Server Metrics 2026-03-17 15:15:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 73795.8 (20h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 807232
telemt_connections_bad_total 6049
telemt_handshake_timeouts_total 23699
telemt_upstream_connect_attempt_total 17599
telemt_upstream_connect_success_total 17139
telemt_upstream_connect_fail_total 460
telemt_upstream_connect_attempts_per_request{bucket="1"} 17599
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8999
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7990
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 460
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 25856
telemt_me_reconnect_success_total 11154
telemt_me_reader_eof_total 12162
telemt_me_idle_close_by_peer_total 12161
telemt_me_route_drop_no_conn_total 338021
telemt_me_route_drop_channel_closed_total 82
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 733112
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5136
telemt_desync_full_logged_total 1422
telemt_desync_suppressed_total 3714
telemt_desync_frames_bucket_total{bucket="1_2"} 1489
telemt_desync_frames_bucket_total{bucket="3_10"} 2037
telemt_desync_frames_bucket_total{bucket="gt_10"} 1610
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 11766
telemt_me_refill_failed_total 454
telemt_me_writer_restored_same_endpoint_total 11132
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 612
telemt_user_connections_total{user="hello"} 734956
telemt_user_connections_current{user="hello"} 1034
telemt_user_octets_from_client{user="hello"} 11896739591 (11.08 GB)
telemt_user_octets_to_client{user="hello"} 244186917239 (227.42 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 354
telemt_user_unique_ips_recent_window{user="hello"} 158
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 74047.3 (20h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 523389
telemt_connections_bad_total 31801
telemt_handshake_timeouts_total 26494
telemt_upstream_connect_attempt_total 90130
telemt_upstream_connect_success_total 89605
telemt_upstream_connect_fail_total 525
telemt_upstream_connect_attempts_per_request{bucket="1"} 90130
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70718
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12388
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6497
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 525
telemt_me_keepalive_timeout_total 329
telemt_me_reconnect_attempts_total 38195
telemt_me_reconnect_success_total 13448
telemt_me_reader_eof_total 14775
telemt_me_idle_close_by_peer_total 14775
telemt_me_route_drop_no_conn_total 192498
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 368295
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1479
telemt_desync_full_logged_total 465
telemt_desync_suppressed_total 1014
telemt_desync_frames_bucket_total{bucket="1_2"} 334
telemt_desync_frames_bucket_total{bucket="3_10"} 647
telemt_desync_frames_bucket_total{bucket="gt_10"} 498
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14384
telemt_me_refill_failed_total 769
telemt_me_writer_restored_same_endpoint_total 13432
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 936
telemt_user_connections_total{user="hello"} 440619
telemt_user_connections_current{user="hello"} 691
telemt_user_octets_from_client{user="hello"} 4897857687 (4.56 GB)
telemt_user_octets_to_client{user="hello"} 128978949029 (120.12 GB)
telemt_user_msgs_from_client{user="hello"} 1056485
telemt_user_msgs_to_client{user="hello"} 3712112
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 73822.9 (20h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 270637
telemt_connections_bad_total 7834
telemt_handshake_timeouts_total 17890
telemt_upstream_connect_attempt_total 19319
telemt_upstream_connect_success_total 19220
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 19319
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8639
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10501
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 27898
telemt_me_reconnect_success_total 15485
telemt_me_reader_eof_total 16737
telemt_me_idle_close_by_peer_total 16734
telemt_me_route_drop_no_conn_total 127402
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 230925
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 811
telemt_desync_full_logged_total 235
telemt_desync_suppressed_total 576
telemt_desync_frames_bucket_total{bucket="1_2"} 294
telemt_desync_frames_bucket_total{bucket="3_10"} 365
telemt_desync_frames_bucket_total{bucket="gt_10"} 152
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 16081
telemt_me_refill_failed_total 385
telemt_me_writer_restored_same_endpoint_total 15474
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 596
telemt_user_connections_total{user="hello"} 230786
telemt_user_connections_current{user="hello"} 348
telemt_user_octets_from_client{user="hello"} 18316730628 (17.06 GB)
telemt_user_octets_to_client{user="hello"} 57101993964 (53.18 GB)
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 73882.3 (20h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 624259
telemt_connections_bad_total 8648
telemt_handshake_timeouts_total 13691
telemt_upstream_connect_attempt_total 16863
telemt_upstream_connect_success_total 16705
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 16863
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8392
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8193
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 26755
telemt_me_reconnect_success_total 11940
telemt_me_reader_eof_total 13053
telemt_me_idle_close_by_peer_total 13052
telemt_me_route_drop_no_conn_total 250914
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 536678
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1853
telemt_desync_full_logged_total 628
telemt_desync_suppressed_total 1225
telemt_desync_frames_bucket_total{bucket="1_2"} 468
telemt_desync_frames_bucket_total{bucket="3_10"} 830
telemt_desync_frames_bucket_total{bucket="gt_10"} 555
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12610
telemt_me_refill_failed_total 458
telemt_me_writer_restored_same_endpoint_total 11931
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 670
telemt_user_connections_total{user="hello"} 537499
telemt_user_connections_current{user="hello"} 740
telemt_user_octets_from_client{user="hello"} 6558359642 (6.11 GB)
telemt_user_octets_to_client{user="hello"} 167997842491 (156.46 GB)
telemt_user_msgs_from_client{user="hello"} 4070
telemt_user_msgs_to_client{user="hello"} 5224
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 73854.2 (20h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 291661
telemt_connections_bad_total 57399
telemt_handshake_timeouts_total 3647
telemt_upstream_connect_attempt_total 21329
telemt_upstream_connect_success_total 20858
telemt_upstream_connect_fail_total 471
telemt_upstream_connect_attempts_per_request{bucket="1"} 21329
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9366
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11201
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 291
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 471
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 41222
telemt_me_reconnect_success_total 16750
telemt_me_reader_eof_total 18105
telemt_me_idle_close_by_peer_total 18103
telemt_me_route_drop_no_conn_total 82565
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 218325
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1120
telemt_desync_full_logged_total 238
telemt_desync_suppressed_total 882
telemt_desync_frames_bucket_total{bucket="1_2"} 560
telemt_desync_frames_bucket_total{bucket="3_10"} 431
telemt_desync_frames_bucket_total{bucket="gt_10"} 129
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 17794
telemt_me_refill_failed_total 760
telemt_me_writer_restored_same_endpoint_total 16742
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1044
telemt_user_connections_total{user="hello"} 218828
telemt_user_connections_current{user="hello"} 252
telemt_user_octets_from_client{user="hello"} 2732741983 (2.55 GB)
telemt_user_octets_to_client{user="hello"} 80121094787 (74.62 GB)
telemt_user_msgs_from_client{user="hello"} 1159
telemt_user_msgs_to_client{user="hello"} 2341
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 74016.1 (20h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 707106
telemt_connections_bad_total 56398
telemt_handshake_timeouts_total 6985
telemt_upstream_connect_attempt_total 14945
telemt_upstream_connect_success_total 14863
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 14945
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7290
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7549
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 43
telemt_me_reconnect_attempts_total 21420
telemt_me_reconnect_success_total 11124
telemt_me_reader_eof_total 12114
telemt_me_idle_close_by_peer_total 12114
telemt_me_route_drop_no_conn_total 511762
telemt_me_route_drop_channel_closed_total 43
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 716084
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1033
telemt_desync_full_logged_total 369
telemt_desync_suppressed_total 664
telemt_desync_frames_bucket_total{bucket="1_2"} 256
telemt_desync_frames_bucket_total{bucket="3_10"} 415
telemt_desync_frames_bucket_total{bucket="gt_10"} 362
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 11620
telemt_me_refill_failed_total 319
telemt_me_writer_restored_same_endpoint_total 11110
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 496
telemt_user_connections_total{user="hello"} 607853
telemt_user_connections_current{user="hello"} 897
telemt_user_octets_from_client{user="hello"} 8924407756 (8.31 GB)
telemt_user_octets_to_client{user="hello"} 272093528324 (253.41 GB)
telemt_user_unique_ips_current{user="hello"} 321
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 21782.3 (6h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16968
telemt_connections_bad_total 73
telemt_handshake_timeouts_total 309
telemt_upstream_connect_attempt_total 11858
telemt_upstream_connect_success_total 11759
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 11858
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6359
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5363
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 22026
telemt_me_reconnect_success_total 10466
telemt_me_reader_eof_total 11093
telemt_me_idle_close_by_peer_total 11093
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 6284
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16164
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 10932
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 10451
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 466
telemt_user_connections_total{user="hello"} 16262
telemt_user_connections_current{user="hello"} 57
telemt_user_octets_from_client{user="hello"} 493048865 (470.21 MB)
telemt_user_octets_to_client{user="hello"} 23550111030 (21.93 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 6
```