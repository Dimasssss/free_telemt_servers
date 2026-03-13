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

# Server Metrics 2026-03-13 20:31:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 133073.1 (36h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 561161
telemt_connections_bad_total 15162
telemt_handshake_timeouts_total 12611
telemt_upstream_connect_attempt_total 33728
telemt_upstream_connect_success_total 33557
telemt_upstream_connect_fail_total 171
telemt_upstream_connect_attempts_per_request{bucket="1"} 33728
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15418
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17994
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 171
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5062
telemt_me_reconnect_attempts_total 31185
telemt_me_reconnect_success_total 26533
telemt_me_reader_eof_total 28324
telemt_me_idle_close_by_peer_total 28323
telemt_me_route_drop_no_conn_total 185570
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 483710
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1535
telemt_desync_full_logged_total 523
telemt_desync_suppressed_total 1012
telemt_desync_frames_bucket_total{bucket="1_2"} 333
telemt_desync_frames_bucket_total{bucket="3_10"} 564
telemt_desync_frames_bucket_total{bucket="gt_10"} 638
telemt_pool_swap_total 118
telemt_me_writer_removed_unexpected_total 26977
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 26517
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 444
telemt_user_connections_total{user="hello"} 483605
telemt_user_connections_current{user="hello"} 263
telemt_user_octets_from_client{user="hello"} 9641822046 (8.98 GB)
telemt_user_octets_to_client{user="hello"} 233365066536 (217.34 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 132966.6 (36h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 283579
telemt_connections_bad_total 2101
telemt_handshake_timeouts_total 1881
telemt_upstream_connect_attempt_total 133784
telemt_upstream_connect_success_total 132810
telemt_upstream_connect_fail_total 974
telemt_upstream_connect_attempts_per_request{bucket="1"} 133784
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 101656
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28780
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2374
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 974
telemt_me_keepalive_timeout_total 3649
telemt_me_reconnect_attempts_total 140780
telemt_me_reconnect_success_total 26429
telemt_me_reader_eof_total 30734
telemt_me_idle_close_by_peer_total 30734
telemt_me_route_drop_no_conn_total 84027
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 169416
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 34
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
telemt_me_writer_removed_unexpected_total 30247
telemt_me_refill_failed_total 3568
telemt_me_writer_restored_same_endpoint_total 26412
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3818
telemt_user_connections_total{user="hello"} 268960
telemt_user_connections_current{user="hello"} 152
telemt_user_octets_from_client{user="hello"} 2804185925 (2.61 GB)
telemt_user_octets_to_client{user="hello"} 81355721479 (75.77 GB)
telemt_user_msgs_from_client{user="hello"} 1622574
telemt_user_msgs_to_client{user="hello"} 8924203
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 132930.5 (36h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 329884
telemt_connections_bad_total 2644
telemt_handshake_timeouts_total 24170
telemt_upstream_connect_attempt_total 35284
telemt_upstream_connect_success_total 35279
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 35284
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16310
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18927
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2809
telemt_me_reconnect_attempts_total 29848
telemt_me_reconnect_success_total 28609
telemt_me_reader_eof_total 30679
telemt_me_idle_close_by_peer_total 30679
telemt_me_route_drop_no_conn_total 117989
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 291524
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
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
telemt_pool_swap_total 122
telemt_me_writer_removed_unexpected_total 28932
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 28589
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 323
telemt_user_connections_total{user="hello"} 291437
telemt_user_connections_current{user="hello"} 157
telemt_user_octets_from_client{user="hello"} 11877690080 (11.06 GB)
telemt_user_octets_to_client{user="hello"} 121883603404 (113.51 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 132905.9 (36h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 435953
telemt_connections_bad_total 15236
telemt_handshake_timeouts_total 4177
telemt_upstream_connect_attempt_total 63384
telemt_upstream_connect_success_total 53070
telemt_upstream_connect_fail_total 10314
telemt_upstream_connect_attempts_per_request{bucket="1"} 63384
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33119
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19644
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 298
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10314
telemt_me_keepalive_timeout_total 4763
telemt_me_reconnect_attempts_total 121844
telemt_me_reconnect_success_total 27410
telemt_me_reader_eof_total 31137
telemt_me_idle_close_by_peer_total 31130
telemt_me_route_drop_no_conn_total 151344
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 366950
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1510
telemt_desync_full_logged_total 448
telemt_desync_suppressed_total 1062
telemt_desync_frames_bucket_total{bucket="1_2"} 363
telemt_desync_frames_bucket_total{bucket="3_10"} 571
telemt_desync_frames_bucket_total{bucket="gt_10"} 576
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 30708
telemt_me_refill_failed_total 2945
telemt_me_writer_restored_same_endpoint_total 27400
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3298
telemt_user_connections_total{user="hello"} 385807
telemt_user_connections_current{user="hello"} 207
telemt_user_octets_from_client{user="hello"} 8715616743 (8.12 GB)
telemt_user_octets_to_client{user="hello"} 142516910924 (132.73 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 83077.5 (23h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 142164
telemt_connections_bad_total 19278
telemt_handshake_timeouts_total 1440
telemt_upstream_connect_attempt_total 31563
telemt_upstream_connect_success_total 31259
telemt_upstream_connect_fail_total 304
telemt_upstream_connect_attempts_per_request{bucket="1"} 31563
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16119
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15035
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 105
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 304
telemt_me_keepalive_timeout_total 1270
telemt_me_reconnect_attempts_total 35592
telemt_me_reconnect_success_total 22200
telemt_me_reader_eof_total 23785
telemt_me_idle_close_by_peer_total 23785
telemt_me_route_drop_no_conn_total 43957
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 112041
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 604
telemt_desync_full_logged_total 140
telemt_desync_suppressed_total 464
telemt_desync_frames_bucket_total{bucket="1_2"} 85
telemt_desync_frames_bucket_total{bucket="3_10"} 302
telemt_desync_frames_bucket_total{bucket="gt_10"} 217
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 22826
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 22182
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 626
telemt_user_connections_total{user="hello"} 116935
telemt_user_connections_current{user="hello"} 69
telemt_user_octets_from_client{user="hello"} 1366876689 (1.27 GB)
telemt_user_octets_to_client{user="hello"} 52718912351 (49.10 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 132862.1 (36h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 812583
telemt_connections_bad_total 24940
telemt_handshake_timeouts_total 24975
telemt_upstream_connect_attempt_total 27410
telemt_upstream_connect_success_total 27265
telemt_upstream_connect_fail_total 145
telemt_upstream_connect_attempts_per_request{bucket="1"} 27410
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12744
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14485
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 145
telemt_me_keepalive_timeout_total 3093
telemt_me_reconnect_attempts_total 25324
telemt_me_reconnect_success_total 20675
telemt_me_reader_eof_total 22173
telemt_me_idle_close_by_peer_total 22170
telemt_me_route_drop_no_conn_total 386997
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 762020
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 691
telemt_desync_full_logged_total 225
telemt_desync_suppressed_total 466
telemt_desync_frames_bucket_total{bucket="1_2"} 247
telemt_desync_frames_bucket_total{bucket="3_10"} 226
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 123
telemt_me_writer_removed_unexpected_total 21095
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 20668
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 420
telemt_user_connections_total{user="hello"} 734887
telemt_user_connections_current{user="hello"} 460
telemt_user_octets_from_client{user="hello"} 12874844968 (11.99 GB)
telemt_user_octets_to_client{user="hello"} 362522563408 (337.63 GB)
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 46
```