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

# Server Metrics 2026-03-19 10:49:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 46874.9 (13h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1079537
telemt_connections_bad_total 92842
telemt_connections_current 1529
telemt_connections_me_current 1529
telemt_handshake_timeouts_total 38116
telemt_upstream_connect_attempt_total 8900
telemt_upstream_connect_success_total 8742
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 8900
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4257
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4482
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 91
telemt_me_reconnect_attempts_total 7555
telemt_me_reconnect_success_total 6390
telemt_me_reader_eof_total 6751
telemt_me_idle_close_by_peer_total 6748
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 414272
telemt_me_route_drop_channel_closed_total 162
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 836716
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 35
telemt_me_endpoint_quarantine_total 32
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4727
telemt_desync_full_logged_total 1453
telemt_desync_suppressed_total 3274
telemt_desync_frames_bucket_total{bucket="1_2"} 1557
telemt_desync_frames_bucket_total{bucket="3_10"} 1726
telemt_desync_frames_bucket_total{bucket="gt_10"} 1444
telemt_pool_swap_total 38
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 6517
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 6369
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 127
telemt_user_connections_total{user="hello"} 830672
telemt_user_connections_current{user="hello"} 1529
telemt_user_octets_from_client{user="hello"} 12521797592 (11.66 GB)
telemt_user_octets_to_client{user="hello"} 257321240340 (239.65 GB)
telemt_user_unique_ips_current{user="hello"} 525
telemt_user_unique_ips_recent_window{user="hello"} 216
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 46879.1 (13h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2727743
telemt_connections_bad_total 165092
telemt_connections_current 3833
telemt_connections_me_current 3833
telemt_handshake_timeouts_total 55742
telemt_upstream_connect_attempt_total 8956
telemt_upstream_connect_success_total 8792
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 8956
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4424
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4341
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 9828
telemt_me_reconnect_success_total 6415
telemt_me_reader_eof_total 6839
telemt_me_idle_close_by_peer_total 6838
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 1521679
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2281065
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9864
telemt_desync_full_logged_total 3289
telemt_desync_suppressed_total 6575
telemt_desync_frames_bucket_total{bucket="1_2"} 1866
telemt_desync_frames_bucket_total{bucket="3_10"} 3873
telemt_desync_frames_bucket_total{bucket="gt_10"} 4125
telemt_pool_swap_total 33
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 6638
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 6393
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 223
telemt_user_connections_total{user="hello"} 2280725
telemt_user_connections_current{user="hello"} 3833
telemt_user_octets_from_client{user="hello"} 33443143484 (31.15 GB)
telemt_user_octets_to_client{user="hello"} 775901830496 (722.61 GB)
telemt_user_unique_ips_current{user="hello"} 1384
telemt_user_unique_ips_recent_window{user="hello"} 920
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 46876.5 (13h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2279051
telemt_connections_bad_total 266016
telemt_connections_current 2975
telemt_connections_me_current 2975
telemt_handshake_timeouts_total 49909
telemt_upstream_connect_attempt_total 8328
telemt_upstream_connect_success_total 8328
telemt_upstream_connect_attempts_per_request{bucket="1"} 8328
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4365
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3947
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 6001
telemt_me_reconnect_success_total 5962
telemt_me_reader_eof_total 6304
telemt_me_idle_close_by_peer_total 6304
telemt_me_route_drop_no_conn_total 1409718
telemt_me_route_drop_channel_closed_total 71
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1791534
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7638
telemt_desync_full_logged_total 2437
telemt_desync_suppressed_total 5201
telemt_desync_frames_bucket_total{bucket="1_2"} 1696
telemt_desync_frames_bucket_total{bucket="3_10"} 2820
telemt_desync_frames_bucket_total{bucket="gt_10"} 3122
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 6067
telemt_me_writer_restored_same_endpoint_total 5946
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 105
telemt_user_connections_total{user="hello"} 1789867
telemt_user_connections_current{user="hello"} 2975
telemt_user_octets_from_client{user="hello"} 25338250660 (23.60 GB)
telemt_user_octets_to_client{user="hello"} 769846750564 (716.98 GB)
telemt_user_unique_ips_current{user="hello"} 1054
telemt_user_unique_ips_recent_window{user="hello"} 443
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 46929.7 (13h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2257554
telemt_connections_bad_total 123095
telemt_connections_current 2981
telemt_connections_me_current 2981
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 59488
telemt_upstream_connect_attempt_total 16684
telemt_upstream_connect_success_total 16520
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 16684
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11605
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4751
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 162
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 9295
telemt_me_reconnect_success_total 5965
telemt_me_reader_eof_total 6335
telemt_me_idle_close_by_peer_total 6334
telemt_me_route_drop_no_conn_total 1142837
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1714064
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6279
telemt_desync_full_logged_total 2130
telemt_desync_suppressed_total 4149
telemt_desync_frames_bucket_total{bucket="1_2"} 1326
telemt_desync_frames_bucket_total{bucket="3_10"} 2445
telemt_desync_frames_bucket_total{bucket="gt_10"} 2508
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 6390
telemt_me_refill_failed_total 97
telemt_me_writer_restored_same_endpoint_total 5941
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 295
telemt_me_writer_removed_unexpected_minus_restored_total 425
telemt_user_connections_total{user="hello"} 1720253
telemt_user_connections_current{user="hello"} 2981
telemt_user_octets_from_client{user="hello"} 19639874004 (18.29 GB)
telemt_user_octets_to_client{user="hello"} 495996884178 (461.93 GB)
telemt_user_msgs_from_client{user="hello"} 28643
telemt_user_msgs_to_client{user="hello"} 76631
telemt_user_unique_ips_current{user="hello"} 980
telemt_user_unique_ips_recent_window{user="hello"} 458
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 46872.9 (13h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2692701
telemt_connections_bad_total 601635
telemt_connections_current 3478
telemt_connections_me_current 3478
telemt_handshake_timeouts_total 53205
telemt_upstream_connect_attempt_total 8244
telemt_upstream_connect_success_total 8187
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 8244
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4189
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3967
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 7014
telemt_me_reconnect_success_total 5814
telemt_me_reader_eof_total 6179
telemt_me_idle_close_by_peer_total 6178
telemt_me_route_drop_no_conn_total 995621
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1778052
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7887
telemt_desync_full_logged_total 2458
telemt_desync_suppressed_total 5429
telemt_desync_frames_bucket_total{bucket="1_2"} 1549
telemt_desync_frames_bucket_total{bucket="3_10"} 3385
telemt_desync_frames_bucket_total{bucket="gt_10"} 2953
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 5937
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 5790
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 1777121
telemt_user_connections_current{user="hello"} 3478
telemt_user_octets_from_client{user="hello"} 31730237868 (29.55 GB)
telemt_user_octets_to_client{user="hello"} 732379148064 (682.08 GB)
telemt_user_unique_ips_current{user="hello"} 1182
telemt_user_unique_ips_recent_window{user="hello"} 533
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 46885.1 (13h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 469929
telemt_connections_bad_total 18340
telemt_connections_current 834
telemt_connections_me_current 834
telemt_handshake_timeouts_total 3697
telemt_upstream_connect_attempt_total 11761
telemt_upstream_connect_success_total 11469
telemt_upstream_connect_fail_total 292
telemt_upstream_connect_attempts_per_request{bucket="1"} 11761
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5685
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5783
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 292
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 14502
telemt_me_reconnect_success_total 9109
telemt_me_reader_eof_total 9647
telemt_me_idle_close_by_peer_total 9647
telemt_me_route_drop_no_conn_total 240550
telemt_me_route_drop_channel_closed_total 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 424491
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 873
telemt_desync_full_logged_total 293
telemt_desync_suppressed_total 580
telemt_desync_frames_bucket_total{bucket="1_2"} 188
telemt_desync_frames_bucket_total{bucket="3_10"} 337
telemt_desync_frames_bucket_total{bucket="gt_10"} 348
telemt_pool_swap_total 22
telemt_pool_stale_pick_total 194
telemt_me_writer_removed_unexpected_total 9354
telemt_me_refill_failed_total 167
telemt_me_writer_restored_same_endpoint_total 9079
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 245
telemt_user_connections_total{user="hello"} 424441
telemt_user_connections_current{user="hello"} 834
telemt_user_octets_from_client{user="hello"} 6944162116 (6.47 GB)
telemt_user_octets_to_client{user="hello"} 161332007888 (150.25 GB)
telemt_user_unique_ips_current{user="hello"} 332
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 46875.2 (13h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1818349
telemt_connections_bad_total 157371
telemt_connections_current 3256
telemt_connections_me_current 3256
telemt_handshake_timeouts_total 70776
telemt_upstream_connect_attempt_total 9462
telemt_upstream_connect_success_total 9461
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9462
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5112
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4346
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 8432
telemt_me_reconnect_success_total 7076
telemt_me_reader_eof_total 7496
telemt_me_idle_close_by_peer_total 7495
telemt_me_route_drop_no_conn_total 704535
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1502081
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8594
telemt_desync_full_logged_total 2768
telemt_desync_suppressed_total 5826
telemt_desync_frames_bucket_total{bucket="1_2"} 1626
telemt_desync_frames_bucket_total{bucket="3_10"} 3262
telemt_desync_frames_bucket_total{bucket="gt_10"} 3706
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 7208
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 7061
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 1500833
telemt_user_connections_current{user="hello"} 3256
telemt_user_octets_from_client{user="hello"} 21217732676 (19.76 GB)
telemt_user_octets_to_client{user="hello"} 714507510800 (665.44 GB)
telemt_user_unique_ips_current{user="hello"} 1063
telemt_user_unique_ips_recent_window{user="hello"} 448
```