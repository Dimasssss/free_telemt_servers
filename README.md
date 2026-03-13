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

# Server Metrics 2026-03-13 15:40:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 115641.3 (32h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 480158
telemt_connections_bad_total 3413
telemt_handshake_timeouts_total 8828
telemt_upstream_connect_attempt_total 28918
telemt_upstream_connect_success_total 28781
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 28918
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12984
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15733
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2478
telemt_me_reconnect_attempts_total 26528
telemt_me_reconnect_success_total 22993
telemt_me_reader_eof_total 24563
telemt_me_idle_close_by_peer_total 24562
telemt_me_route_drop_no_conn_total 156859
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 421421
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1375
telemt_desync_full_logged_total 484
telemt_desync_suppressed_total 891
telemt_desync_frames_bucket_total{bucket="1_2"} 302
telemt_desync_frames_bucket_total{bucket="3_10"} 493
telemt_desync_frames_bucket_total{bucket="gt_10"} 580
telemt_pool_swap_total 105
telemt_me_writer_removed_unexpected_total 23344
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 22977
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 351
telemt_user_connections_total{user="hello"} 420998
telemt_user_connections_current{user="hello"} 347
telemt_user_octets_from_client{user="hello"} 7529844340 (7.01 GB)
telemt_user_octets_to_client{user="hello"} 196400952016 (182.91 GB)
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 115534.3 (32h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 230868
telemt_connections_bad_total 1840
telemt_handshake_timeouts_total 1656
telemt_upstream_connect_attempt_total 87872
telemt_upstream_connect_success_total 87089
telemt_upstream_connect_fail_total 783
telemt_upstream_connect_attempts_per_request{bucket="1"} 87872
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62057
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24053
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 979
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 783
telemt_me_keepalive_timeout_total 1407
telemt_me_reconnect_attempts_total 114930
telemt_me_reconnect_success_total 26022
telemt_me_reader_eof_total 29558
telemt_me_idle_close_by_peer_total 29558
telemt_me_route_drop_no_conn_total 81522
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 163278
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 29024
telemt_me_refill_failed_total 2774
telemt_me_writer_restored_same_endpoint_total 26005
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3002
telemt_user_connections_total{user="hello"} 218351
telemt_user_connections_current{user="hello"} 185
telemt_user_octets_from_client{user="hello"} 2217382122 (2.07 GB)
telemt_user_octets_to_client{user="hello"} 68836776016 (64.11 GB)
telemt_user_msgs_from_client{user="hello"} 835730
telemt_user_msgs_to_client{user="hello"} 5288631
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 115498.0 (32h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 278071
telemt_connections_bad_total 2433
telemt_handshake_timeouts_total 12989
telemt_upstream_connect_attempt_total 30995
telemt_upstream_connect_success_total 30991
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 30995
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14373
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16587
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2345
telemt_me_reconnect_attempts_total 26383
telemt_me_reconnect_success_total 25162
telemt_me_reader_eof_total 26970
telemt_me_idle_close_by_peer_total 26970
telemt_me_route_drop_no_conn_total 100624
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 252746
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 103
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_pool_swap_total 105
telemt_me_writer_removed_unexpected_total 25440
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 25142
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 278
telemt_user_connections_total{user="hello"} 252659
telemt_user_connections_current{user="hello"} 121
telemt_user_octets_from_client{user="hello"} 9598561304 (8.94 GB)
telemt_user_octets_to_client{user="hello"} 107396612892 (100.02 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 115473.4 (32h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 378553
telemt_connections_bad_total 15048
telemt_handshake_timeouts_total 3767
telemt_upstream_connect_attempt_total 42941
telemt_upstream_connect_success_total 32767
telemt_upstream_connect_fail_total 10174
telemt_upstream_connect_attempts_per_request{bucket="1"} 42941
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16493
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16054
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10174
telemt_me_keepalive_timeout_total 4166
telemt_me_reconnect_attempts_total 104009
telemt_me_reconnect_success_total 23937
telemt_me_reader_eof_total 27147
telemt_me_idle_close_by_peer_total 27140
telemt_me_route_drop_no_conn_total 135722
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 328236
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1321
telemt_desync_full_logged_total 390
telemt_desync_suppressed_total 931
telemt_desync_frames_bucket_total{bucket="1_2"} 323
telemt_desync_frames_bucket_total{bucket="3_10"} 501
telemt_desync_frames_bucket_total{bucket="gt_10"} 497
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 26746
telemt_me_refill_failed_total 2497
telemt_me_writer_restored_same_endpoint_total 23927
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2809
telemt_user_connections_total{user="hello"} 331146
telemt_user_connections_current{user="hello"} 223
telemt_user_octets_from_client{user="hello"} 6918867770 (6.44 GB)
telemt_user_octets_to_client{user="hello"} 123848780221 (115.34 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 65644.9 (18h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 102554
telemt_connections_bad_total 13126
telemt_handshake_timeouts_total 1265
telemt_upstream_connect_attempt_total 26605
telemt_upstream_connect_success_total 26378
telemt_upstream_connect_fail_total 227
telemt_upstream_connect_attempts_per_request{bucket="1"} 26605
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13748
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12555
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 227
telemt_me_keepalive_timeout_total 1047
telemt_me_reconnect_attempts_total 29373
telemt_me_reconnect_success_total 18201
telemt_me_reader_eof_total 19521
telemt_me_idle_close_by_peer_total 19521
telemt_me_route_drop_no_conn_total 31304
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 79931
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 390
telemt_desync_full_logged_total 76
telemt_desync_suppressed_total 314
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 214
telemt_desync_frames_bucket_total{bucket="gt_10"} 124
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 18705
telemt_me_refill_failed_total 347
telemt_me_writer_restored_same_endpoint_total 18183
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 504
telemt_user_connections_total{user="hello"} 84830
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 973393757 (928.30 MB)
telemt_user_octets_to_client{user="hello"} 26076472131 (24.29 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 115430.2 (32h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 696611
telemt_connections_bad_total 22815
telemt_handshake_timeouts_total 22816
telemt_upstream_connect_attempt_total 24222
telemt_upstream_connect_success_total 24100
telemt_upstream_connect_fail_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 24222
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11302
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12773
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 122
telemt_me_keepalive_timeout_total 2553
telemt_me_reconnect_attempts_total 22979
telemt_me_reconnect_success_total 18351
telemt_me_reader_eof_total 19696
telemt_me_idle_close_by_peer_total 19693
telemt_me_route_drop_no_conn_total 330055
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 655060
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 636
telemt_desync_full_logged_total 209
telemt_desync_suppressed_total 427
telemt_desync_frames_bucket_total{bucket="1_2"} 216
telemt_desync_frames_bucket_total{bucket="3_10"} 215
telemt_desync_frames_bucket_total{bucket="gt_10"} 205
telemt_pool_swap_total 107
telemt_me_writer_removed_unexpected_total 18730
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 18344
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 379
telemt_user_connections_total{user="hello"} 628011
telemt_user_connections_current{user="hello"} 493
telemt_user_octets_from_client{user="hello"} 10621804996 (9.89 GB)
telemt_user_octets_to_client{user="hello"} 324344468580 (302.07 GB)
telemt_user_unique_ips_current{user="hello"} 169
telemt_user_unique_ips_recent_window{user="hello"} 70
```