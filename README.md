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

# Server Metrics 2026-03-19 11:30:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 49340.5 (13h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1179888
telemt_connections_bad_total 99568
telemt_connections_current 1678
telemt_connections_me_current 1678
telemt_handshake_timeouts_total 41142
telemt_upstream_connect_attempt_total 9471
telemt_upstream_connect_success_total 9309
telemt_upstream_connect_fail_total 162
telemt_upstream_connect_attempts_per_request{bucket="1"} 9471
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4563
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4743
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 162
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 94
telemt_me_reconnect_attempts_total 8724
telemt_me_reconnect_success_total 6839
telemt_me_reader_eof_total 7239
telemt_me_idle_close_by_peer_total 7236
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 495082
telemt_me_route_drop_channel_closed_total 187
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 922167
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 35
telemt_me_endpoint_quarantine_total 33
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5129
telemt_desync_full_logged_total 1561
telemt_desync_suppressed_total 3568
telemt_desync_frames_bucket_total{bucket="1_2"} 1685
telemt_desync_frames_bucket_total{bucket="3_10"} 1863
telemt_desync_frames_bucket_total{bucket="gt_10"} 1581
telemt_pool_swap_total 39
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 6995
telemt_me_refill_failed_total 58
telemt_me_writer_restored_same_endpoint_total 6818
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 156
telemt_user_connections_total{user="hello"} 916105
telemt_user_connections_current{user="hello"} 1678
telemt_user_octets_from_client{user="hello"} 14072945500 (13.11 GB)
telemt_user_octets_to_client{user="hello"} 279929309892 (260.70 GB)
telemt_user_unique_ips_current{user="hello"} 548
telemt_user_unique_ips_recent_window{user="hello"} 267
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 49345.3 (13h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3151616
telemt_connections_bad_total 202294
telemt_connections_current 3942
telemt_connections_me_current 3942
telemt_handshake_timeouts_total 60304
telemt_upstream_connect_attempt_total 9339
telemt_upstream_connect_success_total 9169
telemt_upstream_connect_fail_total 170
telemt_upstream_connect_attempts_per_request{bucket="1"} 9339
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4634
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4506
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 170
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 14120
telemt_me_reconnect_success_total 6671
telemt_me_reader_eof_total 7221
telemt_me_idle_close_by_peer_total 7220
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 2219867
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2645398
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10768
telemt_desync_full_logged_total 3601
telemt_desync_suppressed_total 7167
telemt_desync_frames_bucket_total{bucket="1_2"} 2091
telemt_desync_frames_bucket_total{bucket="3_10"} 4226
telemt_desync_frames_bucket_total{bucket="gt_10"} 4451
telemt_pool_swap_total 33
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 7021
telemt_me_refill_failed_total 232
telemt_me_writer_restored_same_endpoint_total 6649
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 350
telemt_user_connections_total{user="hello"} 2645015
telemt_user_connections_current{user="hello"} 3942
telemt_user_octets_from_client{user="hello"} 36158456028 (33.68 GB)
telemt_user_octets_to_client{user="hello"} 825505880612 (768.81 GB)
telemt_user_unique_ips_current{user="hello"} 1407
telemt_user_unique_ips_recent_window{user="hello"} 666
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 49395.8 (13h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2519027
telemt_connections_bad_total 133968
telemt_connections_current 3547
telemt_connections_me_current 3547
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 63780
telemt_upstream_connect_attempt_total 17150
telemt_upstream_connect_success_total 16979
telemt_upstream_connect_fail_total 171
telemt_upstream_connect_attempts_per_request{bucket="1"} 17150
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11834
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4976
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 167
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 171
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 10660
telemt_me_reconnect_success_total 6320
telemt_me_reader_eof_total 6736
telemt_me_idle_close_by_peer_total 6735
telemt_me_route_drop_no_conn_total 1531873
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1933373
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6900
telemt_desync_full_logged_total 2327
telemt_desync_suppressed_total 4573
telemt_desync_frames_bucket_total{bucket="1_2"} 1458
telemt_desync_frames_bucket_total{bucket="3_10"} 2706
telemt_desync_frames_bucket_total{bucket="gt_10"} 2736
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 6784
telemt_me_refill_failed_total 128
telemt_me_writer_restored_same_endpoint_total 6296
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 295
telemt_me_writer_removed_unexpected_minus_restored_total 464
telemt_user_connections_total{user="hello"} 1939524
telemt_user_connections_current{user="hello"} 3547
telemt_user_octets_from_client{user="hello"} 22293058224 (20.76 GB)
telemt_user_octets_to_client{user="hello"} 535986193098 (499.18 GB)
telemt_user_msgs_from_client{user="hello"} 28643
telemt_user_msgs_to_client{user="hello"} 76631
telemt_user_unique_ips_current{user="hello"} 1086
telemt_user_unique_ips_recent_window{user="hello"} 635
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 49339.2 (13h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2971537
telemt_connections_bad_total 652087
telemt_connections_current 3619
telemt_connections_me_current 3619
telemt_handshake_timeouts_total 58229
telemt_upstream_connect_attempt_total 8741
telemt_upstream_connect_success_total 8677
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 8741
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4466
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4177
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 7402
telemt_me_reconnect_success_total 6197
telemt_me_reader_eof_total 6584
telemt_me_idle_close_by_peer_total 6583
telemt_me_route_drop_no_conn_total 1096421
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1962098
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8572
telemt_desync_full_logged_total 2660
telemt_desync_suppressed_total 5912
telemt_desync_frames_bucket_total{bucket="1_2"} 1623
telemt_desync_frames_bucket_total{bucket="3_10"} 3714
telemt_desync_frames_bucket_total{bucket="gt_10"} 3235
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 6326
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 6173
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 1961153
telemt_user_connections_current{user="hello"} 3619
telemt_user_octets_from_client{user="hello"} 33983395064 (31.65 GB)
telemt_user_octets_to_client{user="hello"} 791805966696 (737.43 GB)
telemt_user_unique_ips_current{user="hello"} 1226
telemt_user_unique_ips_recent_window{user="hello"} 602
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 49351.5 (13h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 513228
telemt_connections_bad_total 18606
telemt_connections_current 955
telemt_connections_me_current 955
telemt_handshake_timeouts_total 3996
telemt_upstream_connect_attempt_total 12258
telemt_upstream_connect_success_total 11949
telemt_upstream_connect_fail_total 309
telemt_upstream_connect_attempts_per_request{bucket="1"} 12258
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5884
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6063
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 309
telemt_me_keepalive_timeout_total 22
telemt_me_reconnect_attempts_total 17052
telemt_me_reconnect_success_total 9464
telemt_me_reader_eof_total 10093
telemt_me_idle_close_by_peer_total 10093
telemt_me_route_drop_no_conn_total 265877
telemt_me_route_drop_channel_closed_total 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 465513
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 993
telemt_desync_full_logged_total 347
telemt_desync_suppressed_total 646
telemt_desync_frames_bucket_total{bucket="1_2"} 212
telemt_desync_frames_bucket_total{bucket="3_10"} 395
telemt_desync_frames_bucket_total{bucket="gt_10"} 386
telemt_pool_swap_total 23
telemt_pool_stale_pick_total 194
telemt_me_writer_removed_unexpected_total 9788
telemt_me_refill_failed_total 235
telemt_me_writer_restored_same_endpoint_total 9433
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 324
telemt_user_connections_total{user="hello"} 465455
telemt_user_connections_current{user="hello"} 955
telemt_user_octets_from_client{user="hello"} 7481000212 (6.97 GB)
telemt_user_octets_to_client{user="hello"} 171595018976 (159.81 GB)
telemt_user_unique_ips_current{user="hello"} 350
telemt_user_unique_ips_recent_window{user="hello"} 166
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 49341.6 (13h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2082343
telemt_connections_bad_total 174878
telemt_connections_current 2986
telemt_connections_me_current 2986
telemt_handshake_timeouts_total 72596
telemt_upstream_connect_attempt_total 9878
telemt_upstream_connect_success_total 9877
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9878
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5356
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 8748
telemt_me_reconnect_success_total 7380
telemt_me_reader_eof_total 7817
telemt_me_idle_close_by_peer_total 7816
telemt_me_route_drop_no_conn_total 1054250
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1736626
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9434
telemt_desync_full_logged_total 3040
telemt_desync_suppressed_total 6394
telemt_desync_frames_bucket_total{bucket="1_2"} 1793
telemt_desync_frames_bucket_total{bucket="3_10"} 3610
telemt_desync_frames_bucket_total{bucket="gt_10"} 4031
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 7519
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 7365
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 1735321
telemt_user_connections_current{user="hello"} 2986
telemt_user_octets_from_client{user="hello"} 22965486096 (21.39 GB)
telemt_user_octets_to_client{user="hello"} 770966636296 (718.02 GB)
telemt_user_unique_ips_current{user="hello"} 992
telemt_user_unique_ips_recent_window{user="hello"} 409
```