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

# Server Metrics 2026-03-13 19:50:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 130629.3 (36h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 553334
telemt_connections_bad_total 13904
telemt_handshake_timeouts_total 12510
telemt_upstream_connect_attempt_total 33103
telemt_upstream_connect_success_total 32935
telemt_upstream_connect_fail_total 168
telemt_upstream_connect_attempts_per_request{bucket="1"} 33103
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15162
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17631
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 142
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 168
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5048
telemt_me_reconnect_attempts_total 30650
telemt_me_reconnect_success_total 25999
telemt_me_reader_eof_total 27757
telemt_me_idle_close_by_peer_total 27756
telemt_me_route_drop_no_conn_total 182979
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 477444
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
telemt_pool_swap_total 117
telemt_me_writer_removed_unexpected_total 26437
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 25983
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 438
telemt_user_connections_total{user="hello"} 477339
telemt_user_connections_current{user="hello"} 265
telemt_user_octets_from_client{user="hello"} 8812970818 (8.21 GB)
telemt_user_octets_to_client{user="hello"} 227969219160 (212.31 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 130522.4 (36h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 277627
telemt_connections_bad_total 2098
telemt_handshake_timeouts_total 1875
telemt_upstream_connect_attempt_total 128655
telemt_upstream_connect_success_total 127712
telemt_upstream_connect_fail_total 943
telemt_upstream_connect_attempts_per_request{bucket="1"} 128655
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 97177
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28260
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2275
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 943
telemt_me_keepalive_timeout_total 3614
telemt_me_reconnect_attempts_total 136566
telemt_me_reconnect_success_total 26345
telemt_me_reader_eof_total 30526
telemt_me_idle_close_by_peer_total 30526
telemt_me_route_drop_no_conn_total 83719
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 168492
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 33
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
telemt_me_writer_removed_unexpected_total 30034
telemt_me_refill_failed_total 3439
telemt_me_writer_restored_same_endpoint_total 26328
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3689
telemt_user_connections_total{user="hello"} 263153
telemt_user_connections_current{user="hello"} 155
telemt_user_octets_from_client{user="hello"} 2714453900 (2.53 GB)
telemt_user_octets_to_client{user="hello"} 79299681623 (73.85 GB)
telemt_user_msgs_from_client{user="hello"} 1511988
telemt_user_msgs_to_client{user="hello"} 8343239
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 130486.0 (36h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 324580
telemt_connections_bad_total 2635
telemt_handshake_timeouts_total 22573
telemt_upstream_connect_attempt_total 34599
telemt_upstream_connect_success_total 34594
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 34599
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16003
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18550
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2790
telemt_me_reconnect_attempts_total 29293
telemt_me_reconnect_success_total 28055
telemt_me_reader_eof_total 30096
telemt_me_idle_close_by_peer_total 30096
telemt_me_route_drop_no_conn_total 116049
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 288065
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
telemt_pool_swap_total 120
telemt_me_writer_removed_unexpected_total 28373
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 28035
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 318
telemt_user_connections_total{user="hello"} 287976
telemt_user_connections_current{user="hello"} 110
telemt_user_octets_from_client{user="hello"} 11791623044 (10.98 GB)
telemt_user_octets_to_client{user="hello"} 120439168504 (112.17 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 130461.6 (36h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 429288
telemt_connections_bad_total 15228
telemt_handshake_timeouts_total 4155
telemt_upstream_connect_attempt_total 62646
telemt_upstream_connect_success_total 52353
telemt_upstream_connect_fail_total 10293
telemt_upstream_connect_attempts_per_request{bucket="1"} 62646
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32773
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19274
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 297
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10293
telemt_me_keepalive_timeout_total 4749
telemt_me_reconnect_attempts_total 117449
telemt_me_reconnect_success_total 26826
telemt_me_reader_eof_total 30426
telemt_me_idle_close_by_peer_total 30419
telemt_me_route_drop_no_conn_total 148630
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 360479
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1464
telemt_desync_full_logged_total 436
telemt_desync_suppressed_total 1028
telemt_desync_frames_bucket_total{bucket="1_2"} 353
telemt_desync_frames_bucket_total{bucket="3_10"} 556
telemt_desync_frames_bucket_total{bucket="gt_10"} 555
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 29996
telemt_me_refill_failed_total 2826
telemt_me_writer_restored_same_endpoint_total 26816
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3170
telemt_user_connections_total{user="hello"} 379344
telemt_user_connections_current{user="hello"} 152
telemt_user_octets_from_client{user="hello"} 8602183439 (8.01 GB)
telemt_user_octets_to_client{user="hello"} 137055030312 (127.64 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 80632.8 (22h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 136948
telemt_connections_bad_total 17277
telemt_handshake_timeouts_total 1427
telemt_upstream_connect_attempt_total 30857
telemt_upstream_connect_success_total 30563
telemt_upstream_connect_fail_total 294
telemt_upstream_connect_attempts_per_request{bucket="1"} 30857
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15771
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14690
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 294
telemt_me_keepalive_timeout_total 1251
telemt_me_reconnect_attempts_total 35025
telemt_me_reconnect_success_total 21634
telemt_me_reader_eof_total 23182
telemt_me_idle_close_by_peer_total 23182
telemt_me_route_drop_no_conn_total 42887
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 108920
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
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 22251
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 21616
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 617
telemt_user_connections_total{user="hello"} 113814
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 1324527501 (1.23 GB)
telemt_user_octets_to_client{user="hello"} 48588168859 (45.25 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 130417.5 (36h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 798928
telemt_connections_bad_total 24805
telemt_handshake_timeouts_total 24898
telemt_upstream_connect_attempt_total 26853
telemt_upstream_connect_success_total 26711
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 26853
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12481
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14194
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_keepalive_timeout_total 3061
telemt_me_reconnect_attempts_total 24902
telemt_me_reconnect_success_total 20255
telemt_me_reader_eof_total 21732
telemt_me_idle_close_by_peer_total 21729
telemt_me_route_drop_no_conn_total 380290
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 749138
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
telemt_pool_swap_total 121
telemt_me_writer_removed_unexpected_total 20671
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 20248
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 416
telemt_user_connections_total{user="hello"} 722002
telemt_user_connections_current{user="hello"} 445
telemt_user_octets_from_client{user="hello"} 12504763276 (11.65 GB)
telemt_user_octets_to_client{user="hello"} 354605927032 (330.25 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 50
```