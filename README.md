# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 19 апреля
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

# Server Metrics 2026-03-19 23:31:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 22439.9 (6h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 466356
telemt_connections_bad_total 29583
telemt_connections_current 743
telemt_connections_me_current 743
telemt_handshake_timeouts_total 7154
telemt_upstream_connect_attempt_total 3718
telemt_upstream_connect_success_total 3687
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 3718
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1800
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1873
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 2586
telemt_me_reconnect_success_total 2567
telemt_me_reader_eof_total 2722
telemt_me_idle_close_by_peer_total 2722
telemt_me_route_drop_no_conn_total 138656
telemt_me_route_drop_channel_closed_total 53
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 370080
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1951
telemt_desync_full_logged_total 684
telemt_desync_suppressed_total 1267
telemt_desync_frames_bucket_total{bucket="1_2"} 406
telemt_desync_frames_bucket_total{bucket="3_10"} 637
telemt_desync_frames_bucket_total{bucket="gt_10"} 908
telemt_pool_swap_total 24
telemt_me_writer_close_signal_drop_total 36
telemt_me_writer_removed_unexpected_total 2619
telemt_me_writer_restored_same_endpoint_total 2554
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 370352
telemt_user_connections_current{user="hello"} 743
telemt_user_octets_from_client{user="hello"} 24366784828 (22.69 GB)
telemt_user_octets_to_client{user="hello"} 136325098900 (126.96 GB)
telemt_user_unique_ips_current{user="hello"} 288
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 38895.2 (10h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2871069
telemt_connections_bad_total 122916
telemt_connections_current 1355
telemt_connections_me_current 1355
telemt_handshake_timeouts_total 59030
telemt_upstream_connect_attempt_total 7811
telemt_upstream_connect_success_total 7684
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 7811
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4609
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3022
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 8724
telemt_me_reconnect_success_total 4489
telemt_me_reader_eof_total 4817
telemt_me_idle_close_by_peer_total 4817
telemt_me_route_drop_no_conn_total 1467153
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2454761
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10725
telemt_desync_full_logged_total 3539
telemt_desync_suppressed_total 7186
telemt_desync_frames_bucket_total{bucket="1_2"} 2008
telemt_desync_frames_bucket_total{bucket="3_10"} 4207
telemt_desync_frames_bucket_total{bucket="gt_10"} 4510
telemt_pool_swap_total 32
telemt_me_writer_close_signal_drop_total 50
telemt_me_writer_removed_unexpected_total 4669
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 4434
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 180
telemt_user_connections_total{user="hello"} 2454589
telemt_user_connections_current{user="hello"} 1355
telemt_user_octets_from_client{user="hello"} 38316267058 (35.68 GB)
telemt_user_octets_to_client{user="hello"} 887031300702 (826.11 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 634
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 38873.4 (10h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2794561
telemt_connections_bad_total 464882
telemt_connections_current 1112
telemt_connections_me_current 1112
telemt_handshake_timeouts_total 37302
telemt_upstream_connect_attempt_total 6166
telemt_upstream_connect_success_total 6118
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 6166
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3136
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2966
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 5080
telemt_me_reconnect_success_total 4149
telemt_me_reader_eof_total 4334
telemt_me_idle_close_by_peer_total 4333
telemt_me_route_drop_no_conn_total 1885970
telemt_me_route_drop_channel_closed_total 169
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1944781
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7512
telemt_desync_full_logged_total 2269
telemt_desync_suppressed_total 5243
telemt_desync_frames_bucket_total{bucket="1_2"} 1849
telemt_desync_frames_bucket_total{bucket="3_10"} 2859
telemt_desync_frames_bucket_total{bucket="gt_10"} 2804
telemt_pool_swap_total 37
telemt_me_writer_close_signal_drop_total 64
telemt_me_writer_removed_unexpected_total 4186
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 4148
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 1940572
telemt_user_connections_current{user="hello"} 1112
telemt_user_octets_from_client{user="hello"} 29134037372 (27.13 GB)
telemt_user_octets_to_client{user="hello"} 737756910232 (687.09 GB)
telemt_user_unique_ips_current{user="hello"} 491
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 38861.3 (10h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2435131
telemt_connections_bad_total 100206
telemt_connections_current 1089
telemt_connections_me_current 1089
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 29907
telemt_upstream_connect_attempt_total 53109
telemt_upstream_connect_success_total 48951
telemt_upstream_connect_fail_total 4158
telemt_upstream_connect_attempts_per_request{bucket="1"} 53109
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41630
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6777
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 519
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4158
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 7417
telemt_me_reconnect_success_total 4662
telemt_me_reader_eof_total 4828
telemt_me_idle_close_by_peer_total 4827
telemt_me_route_drop_no_conn_total 1840144
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2053559
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8144
telemt_desync_full_logged_total 2569
telemt_desync_suppressed_total 5575
telemt_desync_frames_bucket_total{bucket="1_2"} 1995
telemt_desync_frames_bucket_total{bucket="3_10"} 2961
telemt_desync_frames_bucket_total{bucket="gt_10"} 3188
telemt_pool_swap_total 24
telemt_me_writer_close_signal_drop_total 403
telemt_me_writer_removed_unexpected_total 5231
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 4658
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 569
telemt_user_connections_total{user="hello"} 2094715
telemt_user_connections_current{user="hello"} 1089
telemt_user_octets_from_client{user="hello"} 34224610675 (31.87 GB)
telemt_user_octets_to_client{user="hello"} 567784582775 (528.79 GB)
telemt_user_msgs_from_client{user="hello"} 239211
telemt_user_msgs_to_client{user="hello"} 1739348
telemt_user_unique_ips_current{user="hello"} 439
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 92584.7 (25h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6147594
telemt_connections_bad_total 1037452
telemt_connections_current 1262
telemt_connections_me_current 1262
telemt_relay_adaptive_promotions_total 27
telemt_relay_adaptive_demotions_total 3535
telemt_relay_adaptive_hard_promotions_total 25
telemt_handshake_timeouts_total 110561
telemt_upstream_connect_attempt_total 116800
telemt_upstream_connect_success_total 85475
telemt_upstream_connect_fail_total 31325
telemt_upstream_connect_attempts_per_request{bucket="1"} 116800
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72994
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11123
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1358
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31325
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 77388
telemt_me_reconnect_success_total 11851
telemt_me_reader_eof_total 12635
telemt_me_idle_close_by_peer_total 12624
telemt_me_route_drop_no_conn_total 2766460
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4343769
telemt_me_writer_pick_total{mode="p2c",result="full"} 8278
telemt_me_writer_pick_total{mode="p2c",result="closed"} 806
telemt_me_writer_pick_blocking_fallback_total 9050
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 19116
telemt_desync_full_logged_total 5991
telemt_desync_suppressed_total 13125
telemt_desync_frames_bucket_total{bucket="1_2"} 3341
telemt_desync_frames_bucket_total{bucket="3_10"} 7843
telemt_desync_frames_bucket_total{bucket="gt_10"} 7932
telemt_pool_swap_total 78
telemt_me_writer_removed_unexpected_total 12138
telemt_me_refill_failed_total 2043
telemt_me_writer_restored_same_endpoint_total 11826
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 287
telemt_user_connections_total{user="hello"} 4411678
telemt_user_connections_current{user="hello"} 1262
telemt_user_octets_from_client{user="hello"} 67931670282 (63.27 GB)
telemt_user_octets_to_client{user="hello"} 1708733146216 (1.55 TB)
telemt_user_msgs_from_client{user="hello"} 702760
telemt_user_msgs_to_client{user="hello"} 2862853
telemt_user_unique_ips_current{user="hello"} 504
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 38824.5 (10h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 672285
telemt_connections_bad_total 67585
telemt_connections_current 285
telemt_connections_me_current 285
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 12824
telemt_upstream_connect_attempt_total 11956
telemt_upstream_connect_success_total 11626
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 11956
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4783
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6003
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 660
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 330
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 5309
telemt_me_reconnect_success_total 5205
telemt_me_reader_eof_total 5426
telemt_me_idle_close_by_peer_total 5423
telemt_me_route_drop_no_conn_total 455188
telemt_me_route_drop_channel_closed_total 144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 554897
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 881
telemt_me_writer_pick_total{mode="p2c",result="full"} 7065
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_writer_pick_blocking_fallback_total 8012
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1380
telemt_desync_full_logged_total 514
telemt_desync_suppressed_total 866
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 566
telemt_desync_frames_bucket_total{bucket="gt_10"} 596
telemt_pool_swap_total 33
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 150
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 5251
telemt_me_writer_restored_same_endpoint_total 5196
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1203
telemt_me_async_recovery_trigger_total 1464
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 543041
telemt_user_connections_current{user="hello"} 285
telemt_user_octets_from_client{user="hello"} 7067249043 (6.58 GB)
telemt_user_octets_to_client{user="hello"} 131666491122 (122.62 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 38825.9 (10h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1939695
telemt_connections_bad_total 117146
telemt_connections_current 1185
telemt_connections_me_current 1185
telemt_handshake_timeouts_total 35885
telemt_upstream_connect_attempt_total 6718
telemt_upstream_connect_success_total 6666
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 6718
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3566
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3064
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 4727
telemt_me_reconnect_success_total 4690
telemt_me_reader_eof_total 4946
telemt_me_idle_close_by_peer_total 4946
telemt_me_route_drop_no_conn_total 718821
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1669541
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8887
telemt_desync_full_logged_total 2834
telemt_desync_suppressed_total 6053
telemt_desync_frames_bucket_total{bucket="1_2"} 1626
telemt_desync_frames_bucket_total{bucket="3_10"} 3119
telemt_desync_frames_bucket_total{bucket="gt_10"} 4142
telemt_pool_swap_total 38
telemt_me_writer_close_signal_drop_total 36
telemt_me_writer_removed_unexpected_total 4767
telemt_me_writer_restored_same_endpoint_total 4673
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 1668677
telemt_user_connections_current{user="hello"} 1185
telemt_user_octets_from_client{user="hello"} 28297149808 (26.35 GB)
telemt_user_octets_to_client{user="hello"} 844447070820 (786.45 GB)
telemt_user_unique_ips_current{user="hello"} 507
telemt_user_unique_ips_recent_window{user="hello"} 100
```