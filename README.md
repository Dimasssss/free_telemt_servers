# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### **Принимаю донаты криптой для добавления и продления серверов:**
- TON (Можно отправлять TON и USDT в сети TON):
```
UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB
```
### **Спасибо:**
- Ivan Morozov - 20$

_Можете писать свой ник в коментарии к переводу_

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 апреля
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting (2 сервера)
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
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

## rdp-onedash.ru (2 сервера)
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Франция, Париж
- Тариф: Highload-2
- Краткое описание тарифа: 2 vCore, 8 Gb ram, 10 Gbit/s
- Цена в месяц: €12.57
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su (2 сервера)
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

# Server Metrics 2026-03-22 21:01:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 86096.0 (23h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3170129
telemt_connections_bad_total 225473
telemt_connections_current 947
telemt_connections_me_current 947
telemt_handshake_timeouts_total 101130
telemt_upstream_connect_attempt_total 31554
telemt_upstream_connect_success_total 31553
telemt_upstream_connect_attempts_per_request{bucket="1"} 31553
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10863
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20569
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 86
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 1277
telemt_me_reconnect_success_total 525
telemt_me_reader_eof_total 535
telemt_me_idle_close_by_peer_total 535
telemt_me_route_drop_no_conn_total 2821107
telemt_me_route_drop_channel_closed_total 1135
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2675011
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 583
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 667
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 11549
telemt_desync_full_logged_total 3617
telemt_desync_suppressed_total 7932
telemt_desync_frames_bucket_total{bucket="1_2"} 3120
telemt_desync_frames_bucket_total{bucket="3_10"} 4229
telemt_desync_frames_bucket_total{bucket="gt_10"} 4200
telemt_pool_swap_total 95
telemt_pool_force_close_total 2968
telemt_pool_stale_pick_total 22
telemt_me_writer_close_signal_drop_total 603
telemt_me_draining_writers_reap_progress_total 28865
telemt_me_writer_removed_unexpected_total 519
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2098
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26991
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2913
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 55
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25897
telemt_me_writer_teardown_success_total{mode="normal"} 29089
telemt_me_writer_teardown_noop_total 28876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 53506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57965
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 332.235745
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57965
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 603
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 466
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 2665705
telemt_user_connections_current{user="hello"} 947
telemt_user_octets_from_client{user="hello"} 38972293296 (36.30 GB)
telemt_user_octets_to_client{user="hello"} 714618087820 (665.54 GB)
telemt_user_unique_ips_current{user="hello"} 418
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 99461.8 (27h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3883881
telemt_connections_bad_total 343162
telemt_connections_current 431
telemt_connections_me_current 431
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 98718
telemt_upstream_connect_attempt_total 59816
telemt_upstream_connect_success_total 59088
telemt_upstream_connect_fail_total 643
telemt_upstream_connect_attempts_per_request{bucket="1"} 59731
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33006
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25894
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 188
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 643
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 6874
telemt_me_reconnect_success_total 2684
telemt_me_reader_eof_total 2633
telemt_me_idle_close_by_peer_total 2633
telemt_me_route_drop_no_conn_total 3620687
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3096463
telemt_me_endpoint_quarantine_total 757
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 766
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 12512
telemt_desync_full_logged_total 7007
telemt_desync_suppressed_total 5505
telemt_desync_frames_bucket_total{bucket="1_2"} 2835
telemt_desync_frames_bucket_total{bucket="3_10"} 4914
telemt_desync_frames_bucket_total{bucket="gt_10"} 4763
telemt_pool_swap_total 93
telemt_pool_force_close_total 2827
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 234
telemt_me_draining_writers_reap_progress_total 39629
telemt_me_writer_removed_unexpected_total 2576
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4839
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37386
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2400
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 427
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36802
telemt_me_writer_teardown_success_total{mode="normal"} 42225
telemt_me_writer_teardown_noop_total 39630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 79915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 81144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 81469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 81777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 81840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81855
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.360313
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81855
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 234
telemt_me_refill_failed_total 167
telemt_me_writer_restored_same_endpoint_total 2366
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 185
telemt_user_connections_total{user="hello"} 3107163
telemt_user_connections_current{user="hello"} 431
telemt_user_octets_from_client{user="hello"} 40806523767 (38.00 GB)
telemt_user_octets_to_client{user="hello"} 755237247514 (703.37 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 295
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 174321.7 (48h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16052251
telemt_connections_bad_total 1556208
telemt_connections_current 1456
telemt_connections_me_current 1456
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 394201
telemt_upstream_connect_attempt_total 77308
telemt_upstream_connect_success_total 77208
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 77225
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38364
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37146
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1691
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2836
telemt_me_reconnect_success_total 1472
telemt_me_reader_eof_total 1417
telemt_me_idle_close_by_peer_total 1415
telemt_me_route_drop_no_conn_total 14003848
telemt_me_route_drop_channel_closed_total 144
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12794199
telemt_me_endpoint_quarantine_total 1109
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1299
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 52796
telemt_desync_full_logged_total 16660
telemt_desync_suppressed_total 36136
telemt_desync_frames_bucket_total{bucket="1_2"} 11749
telemt_desync_frames_bucket_total{bucket="3_10"} 20565
telemt_desync_frames_bucket_total{bucket="gt_10"} 20482
telemt_pool_swap_total 188
telemt_pool_force_close_total 6331
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1022
telemt_me_draining_writers_reap_progress_total 57337
telemt_me_writer_removed_unexpected_total 1367
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5021
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52962
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 43
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5861
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51006
telemt_me_writer_teardown_success_total{mode="normal"} 57983
telemt_me_writer_teardown_noop_total 57388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 104587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 108079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 109769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 112064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 113718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 114766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 115332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 115362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 115363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 115367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 115369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 115371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 115371
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 313.792174
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 115371
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1022
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 1271
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 12794559
telemt_user_connections_current{user="hello"} 1456
telemt_user_octets_from_client{user="hello"} 188083764061 (175.17 GB)
telemt_user_octets_to_client{user="hello"} 3419804015915 (3.11 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 654
telemt_user_unique_ips_recent_window{user="hello"} 192
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 174323.3 (48h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11633468
telemt_connections_bad_total 1171927
telemt_connections_current 1218
telemt_connections_me_current 1218
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 343397
telemt_upstream_connect_attempt_total 91825
telemt_upstream_connect_success_total 90528
telemt_upstream_connect_fail_total 857
telemt_upstream_connect_attempts_per_request{bucket="1"} 91385
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49387
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37165
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 187
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3789
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 857
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 209
telemt_me_reconnect_attempts_total 4274
telemt_me_reconnect_success_total 1783
telemt_me_reader_eof_total 1641
telemt_me_idle_close_by_peer_total 1641
telemt_me_route_drop_no_conn_total 4523427
telemt_me_route_drop_channel_closed_total 496
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8666401
telemt_me_endpoint_quarantine_total 1104
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1320
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 49
telemt_desync_total 38360
telemt_desync_full_logged_total 12906
telemt_desync_suppressed_total 25454
telemt_desync_frames_bucket_total{bucket="1_2"} 9471
telemt_desync_frames_bucket_total{bucket="3_10"} 14755
telemt_desync_frames_bucket_total{bucket="gt_10"} 14134
telemt_pool_swap_total 185
telemt_pool_force_close_total 5700
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 705
telemt_me_draining_writers_reap_progress_total 55732
telemt_me_writer_removed_unexpected_total 1679
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5184
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52075
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5188
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50032
telemt_me_writer_teardown_success_total{mode="normal"} 57259
telemt_me_writer_teardown_noop_total 55757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 106341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 109510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 110651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 111837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 112592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 112931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 113006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 113008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 113014
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 113016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 113016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 113016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 113016
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 103.791542
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 113016
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 705
telemt_me_refill_failed_total 134
telemt_me_writer_restored_same_endpoint_total 1516
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 8604354
telemt_user_connections_current{user="hello"} 1218
telemt_user_octets_from_client{user="hello"} 216181199788 (201.33 GB)
telemt_user_octets_to_client{user="hello"} 3892875517267 (3.54 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 510
telemt_user_unique_ips_recent_window{user="hello"} 159
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 174298.7 (48h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10893093
telemt_connections_bad_total 944835
telemt_connections_current 788
telemt_connections_me_current 788
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 344479
telemt_upstream_connect_attempt_total 75466
telemt_upstream_connect_success_total 74128
telemt_upstream_connect_fail_total 195
telemt_upstream_connect_attempts_per_request{bucket="1"} 74323
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34575
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35542
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1739
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2272
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 195
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 1417
telemt_me_reconnect_attempts_total 5288
telemt_me_reconnect_success_total 2167
telemt_me_reader_eof_total 1901
telemt_me_idle_close_by_peer_total 1900
telemt_me_route_drop_no_conn_total 5302727
telemt_me_route_drop_channel_closed_total 381
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8242215
telemt_me_endpoint_quarantine_total 1193
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1275
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 66
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 37788
telemt_desync_full_logged_total 12518
telemt_desync_suppressed_total 25270
telemt_desync_frames_bucket_total{bucket="1_2"} 9550
telemt_desync_frames_bucket_total{bucket="3_10"} 14452
telemt_desync_frames_bucket_total{bucket="gt_10"} 13786
telemt_pool_swap_total 182
telemt_pool_force_close_total 5647
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 720
telemt_me_draining_writers_reap_progress_total 55974
telemt_me_writer_removed_unexpected_total 2052
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5755
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52195
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5082
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 565
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50327
telemt_me_writer_teardown_success_total{mode="normal"} 57950
telemt_me_writer_teardown_noop_total 56045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 108239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 110915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 111858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 112919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 113514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 113728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 113856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 113887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 113895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 113908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 113941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 113944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 113995
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.065627
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 113995
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 720
telemt_me_refill_failed_total 165
telemt_me_writer_restored_same_endpoint_total 1871
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 167
telemt_user_connections_total{user="hello"} 8234291
telemt_user_connections_current{user="hello"} 788
telemt_user_octets_from_client{user="hello"} 191648466857 (178.49 GB)
telemt_user_octets_to_client{user="hello"} 3425282441561 (3.12 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 341
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 44567.1 (12h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10942605
telemt_connections_bad_total 663222
telemt_connections_current 1581
telemt_connections_me_current 1581
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 241423
telemt_upstream_connect_attempt_total 49572
telemt_upstream_connect_success_total 47067
telemt_upstream_connect_fail_total 1729
telemt_upstream_connect_attempts_per_request{bucket="1"} 48796
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24250
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15319
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5982
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1729
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6961
telemt_me_reconnect_success_total 1008
telemt_me_reader_eof_total 616
telemt_me_idle_close_by_peer_total 615
telemt_me_route_drop_no_conn_total 25232358
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9087281
telemt_me_endpoint_quarantine_total 310
telemt_me_single_endpoint_outage_enter_total 76
telemt_me_single_endpoint_outage_exit_total 76
telemt_me_single_endpoint_outage_reconnect_attempt_total 135
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 135
telemt_me_single_endpoint_shadow_rotate_total 355
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 42
telemt_desync_total 15064
telemt_desync_full_logged_total 4007
telemt_desync_suppressed_total 11057
telemt_desync_frames_bucket_total{bucket="1_2"} 2831
telemt_desync_frames_bucket_total{bucket="3_10"} 6108
telemt_desync_frames_bucket_total{bucket="gt_10"} 6125
telemt_pool_swap_total 45
telemt_pool_force_close_total 1612
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 445
telemt_me_draining_writers_reap_progress_total 12887
telemt_me_writer_removed_unexpected_total 898
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1942
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11796
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1306
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 306
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11275
telemt_me_writer_teardown_success_total{mode="normal"} 13738
telemt_me_writer_teardown_noop_total 12906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 23004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 24612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 25267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 26099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 26465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 26588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 26644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 26644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 26644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 26644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 26644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 26644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 26644
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 52.080067
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 26644
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 445
telemt_me_refill_failed_total 324
telemt_me_writer_restored_same_endpoint_total 654
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 238
telemt_user_connections_total{user="hello"} 9112044
telemt_user_connections_current{user="hello"} 1581
telemt_user_octets_from_client{user="hello"} 84555473956 (78.75 GB)
telemt_user_octets_to_client{user="hello"} 528538870590 (492.24 GB)
telemt_user_msgs_from_client{user="hello"} 65206
telemt_user_msgs_to_client{user="hello"} 53386
telemt_user_unique_ips_current{user="hello"} 604
telemt_user_unique_ips_recent_window{user="hello"} 194
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 174293.7 (48h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10788194
telemt_connections_bad_total 909664
telemt_connections_current 1472
telemt_connections_me_current 1472
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 237476
telemt_upstream_connect_attempt_total 104407
telemt_upstream_connect_success_total 103312
telemt_upstream_connect_fail_total 934
telemt_upstream_connect_attempts_per_request{bucket="1"} 104246
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62668
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39059
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1347
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 934
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72448
telemt_me_reconnect_success_total 2852
telemt_me_reader_eof_total 2546
telemt_me_idle_close_by_peer_total 2544
telemt_me_route_drop_no_conn_total 5221813
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8525426
telemt_me_endpoint_quarantine_total 1150
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 41
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 41
telemt_me_single_endpoint_shadow_rotate_total 1303
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 51
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 45437
telemt_desync_full_logged_total 15507
telemt_desync_suppressed_total 29930
telemt_desync_frames_bucket_total{bucket="1_2"} 9217
telemt_desync_frames_bucket_total{bucket="3_10"} 17404
telemt_desync_frames_bucket_total{bucket="gt_10"} 18816
telemt_pool_swap_total 178
telemt_pool_force_close_total 5319
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 644
telemt_me_draining_writers_reap_progress_total 59804
telemt_me_writer_removed_unexpected_total 2582
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6319
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 56095
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4589
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 730
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 54485
telemt_me_writer_teardown_success_total{mode="normal"} 62414
telemt_me_writer_teardown_noop_total 59805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 120100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 121483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 121902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 122175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 122209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 122212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 122212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 122215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 122219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 122219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 122219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 122219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 122219
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.109759
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 122219
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 644
telemt_me_refill_failed_total 4287
telemt_me_writer_restored_same_endpoint_total 2401
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 133
telemt_user_connections_total{user="hello"} 8528612
telemt_user_connections_current{user="hello"} 1472
telemt_user_octets_from_client{user="hello"} 193002533621 (179.75 GB)
telemt_user_octets_to_client{user="hello"} 3250646184776 (2.96 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 566
telemt_user_unique_ips_recent_window{user="hello"} 152
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 111129.8 (30h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11401636
telemt_connections_bad_total 456240
telemt_connections_current 995
telemt_connections_me_current 995
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4676203
telemt_upstream_connect_attempt_total 52562
telemt_upstream_connect_success_total 52169
telemt_upstream_connect_fail_total 383
telemt_upstream_connect_attempts_per_request{bucket="1"} 52552
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28478
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23489
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 202
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 383
telemt_me_reconnect_attempts_total 48639
telemt_me_reconnect_success_total 1695
telemt_me_reader_eof_total 1355
telemt_me_idle_close_by_peer_total 1354
telemt_me_route_drop_no_conn_total 4054905
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5497558
telemt_me_endpoint_quarantine_total 719
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 841
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 47
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 30907
telemt_desync_full_logged_total 10500
telemt_desync_suppressed_total 20407
telemt_desync_frames_bucket_total{bucket="1_2"} 6136
telemt_desync_frames_bucket_total{bucket="3_10"} 12233
telemt_desync_frames_bucket_total{bucket="gt_10"} 12538
telemt_pool_swap_total 117
telemt_pool_force_close_total 3562
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 359
telemt_me_draining_writers_reap_progress_total 38803
telemt_me_writer_removed_unexpected_total 1414
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3404
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36848
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3121
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35241
telemt_me_writer_teardown_success_total{mode="normal"} 40252
telemt_me_writer_teardown_noop_total 38810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 77783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 78525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 79062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 79062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79062
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.611123
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79062
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 359
telemt_me_refill_failed_total 2728
telemt_me_writer_restored_same_endpoint_total 1506
telemt_me_writer_restored_fallback_total 19
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5490305
telemt_user_connections_current{user="hello"} 995
telemt_user_octets_from_client{user="hello"} 117819564144 (109.73 GB)
telemt_user_octets_to_client{user="hello"} 2105460250414 (1.91 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 431
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 92100.9 (25h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1396312
telemt_connections_bad_total 34390
telemt_connections_current 831
telemt_connections_me_current 831
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 25859
telemt_upstream_connect_attempt_total 43328
telemt_upstream_connect_success_total 43192
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 43301
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19483
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22967
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 742
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2041
telemt_me_reconnect_success_total 828
telemt_me_reader_eof_total 810
telemt_me_idle_close_by_peer_total 810
telemt_me_route_drop_no_conn_total 486695
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1238883
telemt_me_endpoint_quarantine_total 754
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 759
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 7576
telemt_desync_full_logged_total 2338
telemt_desync_suppressed_total 5238
telemt_desync_frames_bucket_total{bucket="1_2"} 1724
telemt_desync_frames_bucket_total{bucket="3_10"} 2933
telemt_desync_frames_bucket_total{bucket="gt_10"} 2919
telemt_pool_swap_total 99
telemt_pool_force_close_total 2576
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 147
telemt_me_draining_writers_reap_progress_total 36156
telemt_me_writer_removed_unexpected_total 780
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2861
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34108
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2489
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 87
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33580
telemt_me_writer_teardown_success_total{mode="normal"} 36969
telemt_me_writer_teardown_noop_total 36160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 72283
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 72882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 73092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 73129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 73129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 73129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 73129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 73129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 73129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 73129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 73129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 73129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 73129
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.722964
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 73129
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 147
telemt_me_refill_failed_total 67
telemt_me_writer_restored_same_endpoint_total 702
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 1234883
telemt_user_connections_current{user="hello"} 831
telemt_user_octets_from_client{user="hello"} 24110583741 (22.45 GB)
telemt_user_octets_to_client{user="hello"} 522213888239 (486.35 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 290
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 174298.3 (48h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13121071
telemt_connections_bad_total 1547445
telemt_connections_current 1395
telemt_connections_me_current 1395
telemt_handshake_timeouts_total 376471
telemt_upstream_connect_attempt_total 66122
telemt_upstream_connect_success_total 65789
telemt_upstream_connect_fail_total 198
telemt_upstream_connect_attempts_per_request{bucket="1"} 65987
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32608
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33081
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 198
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2579
telemt_me_reconnect_success_total 1356
telemt_me_reader_eof_total 1323
telemt_me_idle_close_by_peer_total 1323
telemt_me_route_drop_no_conn_total 4453016
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 41
telemt_me_route_drop_queue_full_profile_total{profile="high"} 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9921199
telemt_me_endpoint_quarantine_total 1177
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1306
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 41320
telemt_desync_full_logged_total 13456
telemt_desync_suppressed_total 27864
telemt_desync_frames_bucket_total{bucket="1_2"} 9942
telemt_desync_frames_bucket_total{bucket="3_10"} 15218
telemt_desync_frames_bucket_total{bucket="gt_10"} 16160
telemt_pool_swap_total 193
telemt_pool_force_close_total 5293
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 655
telemt_me_draining_writers_reap_progress_total 59615
telemt_me_writer_removed_unexpected_total 1273
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4845
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 56083
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5119
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 54322
telemt_me_writer_teardown_success_total{mode="normal"} 60928
telemt_me_writer_teardown_noop_total 59617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 117987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 119653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 120036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 120412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 120532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 120545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 120545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 120545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 120545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 120545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 120545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 120545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 120545
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.530072
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 120545
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 655
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 1187
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 9888106
telemt_user_connections_current{user="hello"} 1395
telemt_user_octets_from_client{user="hello"} 193317882944 (180.04 GB)
telemt_user_octets_to_client{user="hello"} 4374059409856 (3.98 TB)
telemt_user_unique_ips_current{user="hello"} 496
telemt_user_unique_ips_recent_window{user="hello"} 158
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 174294.7 (48h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11403849
telemt_connections_bad_total 1290060
telemt_connections_current 1090
telemt_connections_me_current 1090
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 300171
telemt_upstream_connect_attempt_total 92571
telemt_upstream_connect_success_total 91739
telemt_upstream_connect_fail_total 625
telemt_upstream_connect_attempts_per_request{bucket="1"} 92364
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50127
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38634
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2065
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 625
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 9929
telemt_me_reconnect_success_total 2393
telemt_me_reader_eof_total 2237
telemt_me_idle_close_by_peer_total 2236
telemt_me_seq_mismatch_total 80
telemt_me_route_drop_no_conn_total 5613474
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8821959
telemt_me_endpoint_quarantine_total 1334
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 48
telemt_me_single_endpoint_outage_exit_total 48
telemt_me_single_endpoint_outage_reconnect_attempt_total 48
telemt_me_single_endpoint_outage_reconnect_success_total 46
telemt_me_single_endpoint_quarantine_bypass_total 48
telemt_me_single_endpoint_shadow_rotate_total 1307
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 40495
telemt_desync_full_logged_total 13058
telemt_desync_suppressed_total 27437
telemt_desync_frames_bucket_total{bucket="1_2"} 10183
telemt_desync_frames_bucket_total{bucket="3_10"} 15002
telemt_desync_frames_bucket_total{bucket="gt_10"} 15310
telemt_pool_swap_total 183
telemt_pool_force_close_total 5089
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 641
telemt_me_draining_writers_reap_progress_total 59345
telemt_me_writer_removed_unexpected_total 2269
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6194
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 55497
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4618
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 54256
telemt_me_writer_teardown_success_total{mode="normal"} 61691
telemt_me_writer_teardown_noop_total 59350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 118385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 120136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 120672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 120991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 121041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 121041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 121041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 121041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 121041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 121041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 121041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 121041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 121041
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.242608
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 121041
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 641
telemt_me_refill_failed_total 389
telemt_me_writer_restored_same_endpoint_total 1949
telemt_me_writer_restored_fallback_total 111
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 209
telemt_user_connections_total{user="hello"} 8827453
telemt_user_connections_current{user="hello"} 1090
telemt_user_octets_from_client{user="hello"} 156137291085 (145.41 GB)
telemt_user_octets_to_client{user="hello"} 3426133794863 (3.12 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 413
telemt_user_unique_ips_recent_window{user="hello"} 127
```