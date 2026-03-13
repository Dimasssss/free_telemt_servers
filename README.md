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

# Server Metrics 2026-03-13 20:05:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 131544.5 (36h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 556343
telemt_connections_bad_total 14492
telemt_handshake_timeouts_total 12560
telemt_upstream_connect_attempt_total 33331
telemt_upstream_connect_success_total 33160
telemt_upstream_connect_fail_total 171
telemt_upstream_connect_attempts_per_request{bucket="1"} 33331
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15257
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17759
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 144
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 171
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5049
telemt_me_reconnect_attempts_total 30831
telemt_me_reconnect_success_total 26180
telemt_me_reader_eof_total 27949
telemt_me_idle_close_by_peer_total 27948
telemt_me_route_drop_no_conn_total 183956
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 479751
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
telemt_me_writer_removed_unexpected_total 26620
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 26164
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 440
telemt_user_connections_total{user="hello"} 479646
telemt_user_connections_current{user="hello"} 286
telemt_user_octets_from_client{user="hello"} 8860097858 (8.25 GB)
telemt_user_octets_to_client{user="hello"} 230077837568 (214.28 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 131438.0 (36h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 279920
telemt_connections_bad_total 2098
telemt_handshake_timeouts_total 1876
telemt_upstream_connect_attempt_total 130757
telemt_upstream_connect_success_total 129805
telemt_upstream_connect_fail_total 952
telemt_upstream_connect_attempts_per_request{bucket="1"} 130757
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 99032
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28443
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2330
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 952
telemt_me_keepalive_timeout_total 3628
telemt_me_reconnect_attempts_total 137976
telemt_me_reconnect_success_total 26378
telemt_me_reader_eof_total 30602
telemt_me_idle_close_by_peer_total 30602
telemt_me_route_drop_no_conn_total 83787
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 168733
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
telemt_me_writer_removed_unexpected_total 30110
telemt_me_refill_failed_total 3482
telemt_me_writer_restored_same_endpoint_total 26361
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3732
telemt_user_connections_total{user="hello"} 265404
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 2730615559 (2.54 GB)
telemt_user_octets_to_client{user="hello"} 79786225085 (74.31 GB)
telemt_user_msgs_from_client{user="hello"} 1554008
telemt_user_msgs_to_client{user="hello"} 8518886
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 131401.7 (36h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 326512
telemt_connections_bad_total 2636
telemt_handshake_timeouts_total 23157
telemt_upstream_connect_attempt_total 34807
telemt_upstream_connect_success_total 34802
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 34807
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16097
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18664
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2802
telemt_me_reconnect_attempts_total 29458
telemt_me_reconnect_success_total 28220
telemt_me_reader_eof_total 30274
telemt_me_idle_close_by_peer_total 30274
telemt_me_route_drop_no_conn_total 116881
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 289326
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
telemt_pool_swap_total 121
telemt_me_writer_removed_unexpected_total 28540
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 28200
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 320
telemt_user_connections_total{user="hello"} 289237
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 11817185364 (11.01 GB)
telemt_user_octets_to_client{user="hello"} 120688216392 (112.40 GB)
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 131377.3 (36h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 431484
telemt_connections_bad_total 15228
telemt_handshake_timeouts_total 4163
telemt_upstream_connect_attempt_total 62966
telemt_upstream_connect_success_total 52668
telemt_upstream_connect_fail_total 10298
telemt_upstream_connect_attempts_per_request{bucket="1"} 62966
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32913
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19449
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 297
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10298
telemt_me_keepalive_timeout_total 4754
telemt_me_reconnect_attempts_total 118938
telemt_me_reconnect_success_total 27097
telemt_me_reader_eof_total 30738
telemt_me_idle_close_by_peer_total 30731
telemt_me_route_drop_no_conn_total 149659
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 362604
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1474
telemt_desync_full_logged_total 439
telemt_desync_suppressed_total 1035
telemt_desync_frames_bucket_total{bucket="1_2"} 354
telemt_desync_frames_bucket_total{bucket="3_10"} 557
telemt_desync_frames_bucket_total{bucket="gt_10"} 563
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 30309
telemt_me_refill_failed_total 2864
telemt_me_writer_restored_same_endpoint_total 27087
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3212
telemt_user_connections_total{user="hello"} 381468
telemt_user_connections_current{user="hello"} 213
telemt_user_octets_from_client{user="hello"} 8639508567 (8.05 GB)
telemt_user_octets_to_client{user="hello"} 138415929836 (128.91 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 81548.9 (22h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 139014
telemt_connections_bad_total 17880
telemt_handshake_timeouts_total 1435
telemt_upstream_connect_attempt_total 31146
telemt_upstream_connect_success_total 30848
telemt_upstream_connect_fail_total 298
telemt_upstream_connect_attempts_per_request{bucket="1"} 31146
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15906
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14839
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 103
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 298
telemt_me_keepalive_timeout_total 1260
telemt_me_reconnect_attempts_total 35267
telemt_me_reconnect_success_total 21876
telemt_me_reader_eof_total 23428
telemt_me_idle_close_by_peer_total 23428
telemt_me_route_drop_no_conn_total 43287
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 110340
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
telemt_me_writer_removed_unexpected_total 22497
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 21858
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 621
telemt_user_connections_total{user="hello"} 115234
telemt_user_connections_current{user="hello"} 101
telemt_user_octets_from_client{user="hello"} 1356985301 (1.26 GB)
telemt_user_octets_to_client{user="hello"} 50977247283 (47.48 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 131333.4 (36h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 804625
telemt_connections_bad_total 24815
telemt_handshake_timeouts_total 24910
telemt_upstream_connect_attempt_total 27080
telemt_upstream_connect_success_total 26937
telemt_upstream_connect_fail_total 143
telemt_upstream_connect_attempts_per_request{bucket="1"} 27080
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12585
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14316
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 143
telemt_me_keepalive_timeout_total 3088
telemt_me_reconnect_attempts_total 25083
telemt_me_reconnect_success_total 20436
telemt_me_reader_eof_total 21916
telemt_me_idle_close_by_peer_total 21913
telemt_me_route_drop_no_conn_total 382984
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 754606
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
telemt_me_writer_removed_unexpected_total 20855
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 20429
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 419
telemt_user_connections_total{user="hello"} 727465
telemt_user_connections_current{user="hello"} 442
telemt_user_octets_from_client{user="hello"} 12598568164 (11.73 GB)
telemt_user_octets_to_client{user="hello"} 356757191096 (332.26 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 45
```