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

# Server Metrics 2026-03-19 06:59:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 33068.1 (9h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 549316
telemt_connections_bad_total 58716
telemt_connections_current 1308
telemt_connections_me_current 1308
telemt_handshake_timeouts_total 23059
telemt_upstream_connect_attempt_total 6391
telemt_upstream_connect_success_total 6277
telemt_upstream_connect_fail_total 114
telemt_upstream_connect_attempts_per_request{bucket="1"} 6391
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3059
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3215
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 114
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 5776
telemt_me_reconnect_success_total 4629
telemt_me_reader_eof_total 4912
telemt_me_idle_close_by_peer_total 4911
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 149972
telemt_me_route_drop_channel_closed_total 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 410049
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2545
telemt_desync_full_logged_total 748
telemt_desync_suppressed_total 1797
telemt_desync_frames_bucket_total{bucket="1_2"} 842
telemt_desync_frames_bucket_total{bucket="3_10"} 992
telemt_desync_frames_bucket_total{bucket="gt_10"} 711
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 4714
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 4612
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 407245
telemt_user_connections_current{user="hello"} 1308
telemt_user_octets_from_client{user="hello"} 5612180116 (5.23 GB)
telemt_user_octets_to_client{user="hello"} 137590012124 (128.14 GB)
telemt_user_unique_ips_current{user="hello"} 486
telemt_user_unique_ips_recent_window{user="hello"} 193
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 33071.9 (9h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1193206
telemt_connections_bad_total 65601
telemt_connections_current 3891
telemt_connections_me_current 3891
telemt_handshake_timeouts_total 30499
telemt_upstream_connect_attempt_total 6170
telemt_upstream_connect_success_total 6057
telemt_upstream_connect_fail_total 113
telemt_upstream_connect_attempts_per_request{bucket="1"} 6170
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3007
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3035
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 113
telemt_me_reconnect_attempts_total 5544
telemt_me_reconnect_success_total 4394
telemt_me_reader_eof_total 4662
telemt_me_idle_close_by_peer_total 4662
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 402130
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 986638
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4359
telemt_desync_full_logged_total 1500
telemt_desync_suppressed_total 2859
telemt_desync_frames_bucket_total{bucket="1_2"} 777
telemt_desync_frames_bucket_total{bucket="3_10"} 1645
telemt_desync_frames_bucket_total{bucket="gt_10"} 1937
telemt_pool_swap_total 28
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 4511
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 4373
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 117
telemt_user_connections_total{user="hello"} 986574
telemt_user_connections_current{user="hello"} 3891
telemt_user_octets_from_client{user="hello"} 20333082988 (18.94 GB)
telemt_user_octets_to_client{user="hello"} 428989126312 (399.53 GB)
telemt_user_unique_ips_current{user="hello"} 1338
telemt_user_unique_ips_recent_window{user="hello"} 605
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 33070.0 (9h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1026740
telemt_connections_bad_total 154427
telemt_connections_current 3097
telemt_connections_me_current 3097
telemt_handshake_timeouts_total 29982
telemt_upstream_connect_attempt_total 5957
telemt_upstream_connect_success_total 5957
telemt_upstream_connect_attempts_per_request{bucket="1"} 5957
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3048
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2901
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 4321
telemt_me_reconnect_success_total 4300
telemt_me_reader_eof_total 4556
telemt_me_idle_close_by_peer_total 4556
telemt_me_route_drop_no_conn_total 325789
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 760811
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3690
telemt_desync_full_logged_total 1169
telemt_desync_suppressed_total 2521
telemt_desync_frames_bucket_total{bucket="1_2"} 700
telemt_desync_frames_bucket_total{bucket="3_10"} 1337
telemt_desync_frames_bucket_total{bucket="gt_10"} 1653
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 4380
telemt_me_writer_restored_same_endpoint_total 4284
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 760477
telemt_user_connections_current{user="hello"} 3097
telemt_user_octets_from_client{user="hello"} 13880720752 (12.93 GB)
telemt_user_octets_to_client{user="hello"} 416937010920 (388.30 GB)
telemt_user_unique_ips_current{user="hello"} 1053
telemt_user_unique_ips_recent_window{user="hello"} 481
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 33122.6 (9h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1077801
telemt_connections_bad_total 89005
telemt_connections_current 2686
telemt_connections_me_current 2686
telemt_handshake_timeouts_total 26658
telemt_upstream_connect_attempt_total 5803
telemt_upstream_connect_success_total 5803
telemt_upstream_connect_attempts_per_request{bucket="1"} 5803
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2931
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2857
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 5191
telemt_me_reconnect_success_total 4137
telemt_me_reader_eof_total 4397
telemt_me_idle_close_by_peer_total 4396
telemt_me_route_drop_no_conn_total 371021
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 747804
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2842
telemt_desync_full_logged_total 1013
telemt_desync_suppressed_total 1829
telemt_desync_frames_bucket_total{bucket="1_2"} 514
telemt_desync_frames_bucket_total{bucket="3_10"} 1127
telemt_desync_frames_bucket_total{bucket="gt_10"} 1201
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 4228
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 4113
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 746682
telemt_user_connections_current{user="hello"} 2686
telemt_user_octets_from_client{user="hello"} 11253758732 (10.48 GB)
telemt_user_octets_to_client{user="hello"} 276004174680 (257.05 GB)
telemt_user_unique_ips_current{user="hello"} 945
telemt_user_unique_ips_recent_window{user="hello"} 440
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 33065.7 (9h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1336582
telemt_connections_bad_total 379522
telemt_connections_current 2961
telemt_connections_me_current 2961
telemt_handshake_timeouts_total 30764
telemt_upstream_connect_attempt_total 5817
telemt_upstream_connect_success_total 5780
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 5817
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2921
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2840
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_reconnect_attempts_total 4154
telemt_me_reconnect_success_total 4125
telemt_me_reader_eof_total 4369
telemt_me_idle_close_by_peer_total 4369
telemt_me_route_drop_no_conn_total 325878
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 795331
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3936
telemt_desync_full_logged_total 1253
telemt_desync_suppressed_total 2683
telemt_desync_frames_bucket_total{bucket="1_2"} 888
telemt_desync_frames_bucket_total{bucket="3_10"} 1757
telemt_desync_frames_bucket_total{bucket="gt_10"} 1291
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 4174
telemt_me_writer_restored_same_endpoint_total 4101
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 795117
telemt_user_connections_current{user="hello"} 2961
telemt_user_octets_from_client{user="hello"} 18076555064 (16.84 GB)
telemt_user_octets_to_client{user="hello"} 407593264424 (379.60 GB)
telemt_user_unique_ips_current{user="hello"} 1050
telemt_user_unique_ips_recent_window{user="hello"} 487
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 33077.4 (9h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 221616
telemt_connections_bad_total 12319
telemt_connections_current 786
telemt_connections_me_current 786
telemt_handshake_timeouts_total 1890
telemt_upstream_connect_attempt_total 8770
telemt_upstream_connect_success_total 8547
telemt_upstream_connect_fail_total 223
telemt_upstream_connect_attempts_per_request{bucket="1"} 8770
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4180
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4367
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 223
telemt_me_reconnect_attempts_total 11334
telemt_me_reconnect_success_total 6893
telemt_me_reader_eof_total 7294
telemt_me_idle_close_by_peer_total 7294
telemt_me_route_drop_no_conn_total 98014
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 195784
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 305
telemt_desync_full_logged_total 112
telemt_desync_suppressed_total 193
telemt_desync_frames_bucket_total{bucket="1_2"} 78
telemt_desync_frames_bucket_total{bucket="3_10"} 139
telemt_desync_frames_bucket_total{bucket="gt_10"} 88
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 7069
telemt_me_refill_failed_total 138
telemt_me_writer_restored_same_endpoint_total 6863
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 176
telemt_user_connections_total{user="hello"} 195768
telemt_user_connections_current{user="hello"} 786
telemt_user_octets_from_client{user="hello"} 3099106212 (2.89 GB)
telemt_user_octets_to_client{user="hello"} 102367506316 (95.34 GB)
telemt_user_unique_ips_current{user="hello"} 306
telemt_user_unique_ips_recent_window{user="hello"} 143
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 33068.3 (9h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 823267
telemt_connections_bad_total 88235
telemt_connections_current 3109
telemt_connections_me_current 3109
telemt_handshake_timeouts_total 35733
telemt_upstream_connect_attempt_total 6713
telemt_upstream_connect_success_total 6713
telemt_upstream_connect_attempts_per_request{bucket="1"} 6713
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3573
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3137
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 5110
telemt_me_reconnect_success_total 5063
telemt_me_reader_eof_total 5334
telemt_me_idle_close_by_peer_total 5334
telemt_me_route_drop_no_conn_total 286660
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 668663
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3803
telemt_desync_full_logged_total 1333
telemt_desync_suppressed_total 2470
telemt_desync_frames_bucket_total{bucket="1_2"} 722
telemt_desync_frames_bucket_total{bucket="3_10"} 1470
telemt_desync_frames_bucket_total{bucket="gt_10"} 1611
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 5117
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 5048
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 668446
telemt_user_connections_current{user="hello"} 3109
telemt_user_octets_from_client{user="hello"} 10163605460 (9.47 GB)
telemt_user_octets_to_client{user="hello"} 387036024232 (360.46 GB)
telemt_user_unique_ips_current{user="hello"} 930
telemt_user_unique_ips_recent_window{user="hello"} 398
```