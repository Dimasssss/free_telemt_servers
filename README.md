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

# Server Metrics 2026-03-14 10:05:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 181954.8 (50h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 706369
telemt_connections_bad_total 33112
telemt_handshake_timeouts_total 13768
telemt_upstream_connect_attempt_total 46221
telemt_upstream_connect_success_total 45986
telemt_upstream_connect_fail_total 235
telemt_upstream_connect_attempts_per_request{bucket="1"} 46221
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21032
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24802
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 235
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5919
telemt_me_reconnect_attempts_total 41228
telemt_me_reconnect_success_total 36525
telemt_me_reader_eof_total 39037
telemt_me_idle_close_by_peer_total 39036
telemt_me_route_drop_no_conn_total 233439
telemt_me_route_drop_channel_closed_total 33
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 604661
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2390
telemt_desync_full_logged_total 800
telemt_desync_suppressed_total 1590
telemt_desync_frames_bucket_total{bucket="1_2"} 510
telemt_desync_frames_bucket_total{bucket="3_10"} 879
telemt_desync_frames_bucket_total{bucket="gt_10"} 1001
telemt_pool_swap_total 166
telemt_me_writer_removed_unexpected_total 37064
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 36505
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 539
telemt_user_connections_total{user="hello"} 604539
telemt_user_connections_current{user="hello"} 407
telemt_user_octets_from_client{user="hello"} 17326731294 (16.14 GB)
telemt_user_octets_to_client{user="hello"} 287955436152 (268.18 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 181847.6 (50h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 354818
telemt_connections_bad_total 2822
telemt_handshake_timeouts_total 3138
telemt_upstream_connect_attempt_total 153675
telemt_upstream_connect_success_total 152329
telemt_upstream_connect_fail_total 1346
telemt_upstream_connect_attempts_per_request{bucket="1"} 153675
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 111458
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38424
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2446
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1346
telemt_me_keepalive_timeout_total 5423
telemt_me_reconnect_attempts_total 188264
telemt_me_reconnect_success_total 39977
telemt_me_reader_eof_total 45663
telemt_me_idle_close_by_peer_total 45663
telemt_me_route_drop_no_conn_total 121551
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 231758
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 45
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
telemt_me_writer_removed_unexpected_total 44990
telemt_me_refill_failed_total 4627
telemt_me_writer_restored_same_endpoint_total 39960
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 5013
telemt_user_connections_total{user="hello"} 334862
telemt_user_connections_current{user="hello"} 152
telemt_user_octets_from_client{user="hello"} 3438022751 (3.20 GB)
telemt_user_octets_to_client{user="hello"} 107137972631 (99.78 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 181811.5 (50h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 411400
telemt_connections_bad_total 3221
telemt_handshake_timeouts_total 35719
telemt_upstream_connect_attempt_total 48144
telemt_upstream_connect_success_total 48135
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 48144
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22031
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26035
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3724
telemt_me_reconnect_attempts_total 40355
telemt_me_reconnect_success_total 39052
telemt_me_reader_eof_total 41974
telemt_me_idle_close_by_peer_total 41974
telemt_me_route_drop_no_conn_total 149465
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 357948
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 136
telemt_desync_full_logged_total 61
telemt_desync_suppressed_total 75
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 46
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 171
telemt_me_writer_removed_unexpected_total 39522
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 39031
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 470
telemt_user_connections_total{user="hello"} 357675
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 13834636104 (12.88 GB)
telemt_user_octets_to_client{user="hello"} 157957919468 (147.11 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 181786.9 (50h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 519243
telemt_connections_bad_total 16710
telemt_handshake_timeouts_total 5211
telemt_upstream_connect_attempt_total 78581
telemt_upstream_connect_success_total 67919
telemt_upstream_connect_fail_total 10662
telemt_upstream_connect_attempts_per_request{bucket="1"} 78581
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39685
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27876
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 349
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10662
telemt_me_keepalive_timeout_total 5573
telemt_me_reconnect_attempts_total 152144
telemt_me_reconnect_success_total 39848
telemt_me_reader_eof_total 44637
telemt_me_idle_close_by_peer_total 44629
telemt_me_route_drop_no_conn_total 188175
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 444128
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1985
telemt_desync_full_logged_total 589
telemt_desync_suppressed_total 1396
telemt_desync_frames_bucket_total{bucket="1_2"} 469
telemt_desync_frames_bucket_total{bucket="3_10"} 764
telemt_desync_frames_bucket_total{bucket="gt_10"} 752
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 43810
telemt_me_refill_failed_total 3501
telemt_me_writer_restored_same_endpoint_total 39838
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3962
telemt_user_connections_total{user="hello"} 462998
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 9960878791 (9.28 GB)
telemt_user_octets_to_client{user="hello"} 191757602056 (178.59 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 131958.3 (36h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 218897
telemt_connections_bad_total 33608
telemt_handshake_timeouts_total 1967
telemt_upstream_connect_attempt_total 46490
telemt_upstream_connect_success_total 46035
telemt_upstream_connect_fail_total 455
telemt_upstream_connect_attempts_per_request{bucket="1"} 46490
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23011
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22873
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 455
telemt_me_keepalive_timeout_total 2704
telemt_me_reconnect_attempts_total 50456
telemt_me_reconnect_success_total 34579
telemt_me_reader_eof_total 37004
telemt_me_idle_close_by_peer_total 37004
telemt_me_route_drop_no_conn_total 66291
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 172544
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 758
telemt_desync_full_logged_total 186
telemt_desync_suppressed_total 572
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 360
telemt_desync_frames_bucket_total{bucket="gt_10"} 271
telemt_pool_swap_total 99
telemt_me_writer_removed_unexpected_total 35389
telemt_me_refill_failed_total 492
telemt_me_writer_restored_same_endpoint_total 34561
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 810
telemt_user_connections_total{user="hello"} 177303
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 2652071329 (2.47 GB)
telemt_user_octets_to_client{user="hello"} 83100893171 (77.39 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 181743.0 (50h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1051648
telemt_connections_bad_total 36940
telemt_handshake_timeouts_total 26855
telemt_upstream_connect_attempt_total 37908
telemt_upstream_connect_success_total 37707
telemt_upstream_connect_fail_total 201
telemt_upstream_connect_attempts_per_request{bucket="1"} 37908
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17818
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19848
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 201
telemt_me_keepalive_timeout_total 4851
telemt_me_reconnect_attempts_total 33421
telemt_me_reconnect_success_total 28736
telemt_me_reader_eof_total 30816
telemt_me_idle_close_by_peer_total 30813
telemt_me_route_drop_no_conn_total 492317
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 974695
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 806
telemt_desync_full_logged_total 266
telemt_desync_suppressed_total 540
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 268
telemt_desync_frames_bucket_total{bucket="gt_10"} 278
telemt_pool_swap_total 170
telemt_me_writer_removed_unexpected_total 29244
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 28729
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 508
telemt_user_connections_total{user="hello"} 947307
telemt_user_connections_current{user="hello"} 461
telemt_user_octets_from_client{user="hello"} 17806247684 (16.58 GB)
telemt_user_octets_to_client{user="hello"} 475346500348 (442.70 GB)
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 78
```