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

# Server Metrics 2026-03-18 00:51:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 108368.5 (30h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1269939
telemt_connections_bad_total 9597
telemt_handshake_timeouts_total 32462
telemt_upstream_connect_attempt_total 24255
telemt_upstream_connect_success_total 23756
telemt_upstream_connect_fail_total 499
telemt_upstream_connect_attempts_per_request{bucket="1"} 24255
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11313
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 499
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 33190
telemt_me_reconnect_success_total 16053
telemt_me_reader_eof_total 17433
telemt_me_idle_close_by_peer_total 17432
telemt_me_route_drop_no_conn_total 558688
telemt_me_route_drop_channel_closed_total 158
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1167598
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7542
telemt_desync_full_logged_total 2211
telemt_desync_suppressed_total 5331
telemt_desync_frames_bucket_total{bucket="1_2"} 2020
telemt_desync_frames_bucket_total{bucket="3_10"} 2857
telemt_desync_frames_bucket_total{bucket="gt_10"} 2665
telemt_pool_swap_total 89
telemt_me_writer_removed_unexpected_total 16825
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 16031
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 772
telemt_user_connections_total{user="hello"} 1161811
telemt_user_connections_current{user="hello"} 549
telemt_user_octets_from_client{user="hello"} 22769729447 (21.21 GB)
telemt_user_octets_to_client{user="hello"} 416493618591 (387.89 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 241
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 108619.9 (30h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1347662
telemt_connections_bad_total 62105
telemt_handshake_timeouts_total 46184
telemt_upstream_connect_attempt_total 466795
telemt_upstream_connect_success_total 465249
telemt_upstream_connect_fail_total 1546
telemt_upstream_connect_attempts_per_request{bucket="1"} 466795
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 389301
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32598
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43348
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1546
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 122344
telemt_me_reconnect_success_total 16914
telemt_me_reader_eof_total 19031
telemt_me_idle_close_by_peer_total 19021
telemt_me_route_drop_no_conn_total 348356
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 728500
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3327
telemt_desync_full_logged_total 1111
telemt_desync_suppressed_total 2216
telemt_desync_frames_bucket_total{bucket="1_2"} 650
telemt_desync_frames_bucket_total{bucket="3_10"} 1373
telemt_desync_frames_bucket_total{bucket="gt_10"} 1304
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 18460
telemt_me_refill_failed_total 3289
telemt_me_writer_restored_same_endpoint_total 16896
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1546
telemt_user_connections_total{user="hello"} 1170849
telemt_user_connections_current{user="hello"} 644
telemt_user_octets_from_client{user="hello"} 15873967469 (14.78 GB)
telemt_user_octets_to_client{user="hello"} 400332929286 (372.84 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 253
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 108395.7 (30h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 799045
telemt_connections_bad_total 52742
telemt_handshake_timeouts_total 24142
telemt_upstream_connect_attempt_total 25468
telemt_upstream_connect_success_total 25323
telemt_upstream_connect_fail_total 145
telemt_upstream_connect_attempts_per_request{bucket="1"} 25468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11605
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13623
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 145
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 40549
telemt_me_reconnect_success_total 19864
telemt_me_reader_eof_total 21639
telemt_me_idle_close_by_peer_total 21632
telemt_me_route_drop_no_conn_total 322264
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 678537
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2165
telemt_desync_full_logged_total 704
telemt_desync_suppressed_total 1461
telemt_desync_frames_bucket_total{bucket="1_2"} 614
telemt_desync_frames_bucket_total{bucket="3_10"} 835
telemt_desync_frames_bucket_total{bucket="gt_10"} 716
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 20781
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 19852
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 917
telemt_user_connections_total{user="hello"} 676680
telemt_user_connections_current{user="hello"} 420
telemt_user_octets_from_client{user="hello"} 34718798036 (32.33 GB)
telemt_user_octets_to_client{user="hello"} 298946127516 (278.42 GB)
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 108455.3 (30h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1284891
telemt_connections_bad_total 53676
telemt_handshake_timeouts_total 21849
telemt_upstream_connect_attempt_total 86582
telemt_upstream_connect_success_total 85160
telemt_upstream_connect_fail_total 1422
telemt_upstream_connect_attempts_per_request{bucket="1"} 86582
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 71489
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13281
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 360
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1422
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 36095
telemt_me_reconnect_success_total 15733
telemt_me_reader_eof_total 17359
telemt_me_idle_close_by_peer_total 17357
telemt_me_route_drop_no_conn_total 525431
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1045795
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3942
telemt_desync_full_logged_total 1304
telemt_desync_suppressed_total 2638
telemt_desync_frames_bucket_total{bucket="1_2"} 966
telemt_desync_frames_bucket_total{bucket="3_10"} 1657
telemt_desync_frames_bucket_total{bucket="gt_10"} 1319
telemt_pool_swap_total 84
telemt_me_writer_removed_unexpected_total 16663
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 15723
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 930
telemt_user_connections_total{user="hello"} 1108915
telemt_user_connections_current{user="hello"} 537
telemt_user_octets_from_client{user="hello"} 17417335939 (16.22 GB)
telemt_user_octets_to_client{user="hello"} 520498519510 (484.75 GB)
telemt_user_msgs_from_client{user="hello"} 738254
telemt_user_msgs_to_client{user="hello"} 5205558
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 108427.2 (30h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 843379
telemt_connections_bad_total 99324
telemt_handshake_timeouts_total 6770
telemt_upstream_connect_attempt_total 44688
telemt_upstream_connect_success_total 44074
telemt_upstream_connect_fail_total 614
telemt_upstream_connect_attempts_per_request{bucket="1"} 44688
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27778
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15884
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 412
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 614
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 57132
telemt_me_reconnect_success_total 22172
telemt_me_reader_eof_total 24088
telemt_me_idle_close_by_peer_total 24086
telemt_me_route_drop_no_conn_total 267511
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 678666
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3180
telemt_desync_full_logged_total 944
telemt_desync_suppressed_total 2236
telemt_desync_frames_bucket_total{bucket="1_2"} 1005
telemt_desync_frames_bucket_total{bucket="3_10"} 1273
telemt_desync_frames_bucket_total{bucket="gt_10"} 902
telemt_pool_swap_total 54
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 23623
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 22164
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1451
telemt_user_connections_total{user="hello"} 695273
telemt_user_connections_current{user="hello"} 427
telemt_user_octets_from_client{user="hello"} 13602409564 (12.67 GB)
telemt_user_octets_to_client{user="hello"} 348414739204 (324.49 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 108588.3 (30h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1085386
telemt_connections_bad_total 106086
telemt_handshake_timeouts_total 9654
telemt_upstream_connect_attempt_total 21591
telemt_upstream_connect_success_total 21472
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 21591
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10257
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11098
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 27346
telemt_me_reconnect_success_total 16063
telemt_me_reader_eof_total 17433
telemt_me_idle_close_by_peer_total 17431
telemt_me_route_drop_no_conn_total 732967
telemt_me_route_drop_channel_closed_total 88
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1051997
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2106
telemt_desync_full_logged_total 737
telemt_desync_suppressed_total 1369
telemt_desync_frames_bucket_total{bucket="1_2"} 461
telemt_desync_frames_bucket_total{bucket="3_10"} 802
telemt_desync_frames_bucket_total{bucket="gt_10"} 843
telemt_pool_swap_total 95
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 16673
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 16049
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 610
telemt_user_connections_total{user="hello"} 899744
telemt_user_connections_current{user="hello"} 441
telemt_user_octets_from_client{user="hello"} 14569244072 (13.57 GB)
telemt_user_octets_to_client{user="hello"} 382650537692 (356.37 GB)
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 56355.5 (15h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 397065
telemt_connections_bad_total 44685
telemt_handshake_timeouts_total 10872
telemt_upstream_connect_attempt_total 21182
telemt_upstream_connect_success_total 20988
telemt_upstream_connect_fail_total 194
telemt_upstream_connect_attempts_per_request{bucket="1"} 21182
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11253
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9639
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 194
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 29618
telemt_me_reconnect_success_total 18018
telemt_me_reader_eof_total 19048
telemt_me_idle_close_by_peer_total 19048
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 99296
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 292467
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1122
telemt_desync_full_logged_total 352
telemt_desync_suppressed_total 770
telemt_desync_frames_bucket_total{bucket="1_2"} 214
telemt_desync_frames_bucket_total{bucket="3_10"} 485
telemt_desync_frames_bucket_total{bucket="gt_10"} 423
telemt_pool_swap_total 35
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 18585
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 17987
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 567
telemt_user_connections_total{user="hello"} 292407
telemt_user_connections_current{user="hello"} 323
telemt_user_octets_from_client{user="hello"} 22262379557 (20.73 GB)
telemt_user_octets_to_client{user="hello"} 243445861174 (226.73 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 27
```