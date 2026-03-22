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

# Server Metrics 2026-03-22 19:59:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 82403.1 (22h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3058039
telemt_connections_bad_total 208662
telemt_connections_current 1207
telemt_connections_me_current 1207
telemt_handshake_timeouts_total 98298
telemt_upstream_connect_attempt_total 30242
telemt_upstream_connect_success_total 30241
telemt_upstream_connect_attempts_per_request{bucket="1"} 30241
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10460
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19674
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 77
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 1197
telemt_me_reconnect_success_total 510
telemt_me_reader_eof_total 516
telemt_me_idle_close_by_peer_total 516
telemt_me_route_drop_no_conn_total 2724289
telemt_me_route_drop_channel_closed_total 1086
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2587880
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 559
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 639
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
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
telemt_desync_total 11121
telemt_desync_full_logged_total 3525
telemt_desync_suppressed_total 7596
telemt_desync_frames_bucket_total{bucket="1_2"} 2971
telemt_desync_frames_bucket_total{bucket="3_10"} 4127
telemt_desync_frames_bucket_total{bucket="gt_10"} 4023
telemt_pool_swap_total 91
telemt_pool_force_close_total 2818
telemt_pool_stale_pick_total 22
telemt_me_writer_close_signal_drop_total 586
telemt_me_draining_writers_reap_progress_total 27640
telemt_me_writer_removed_unexpected_total 500
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2018
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25853
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2765
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24822
telemt_me_writer_teardown_success_total{mode="normal"} 27871
telemt_me_writer_teardown_noop_total 27650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 51380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 53879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 55116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 55517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 55521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 55521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 55521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 55521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 55521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 55521
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 309.376399
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 55521
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 586
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 452
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 2579616
telemt_user_connections_current{user="hello"} 1207
telemt_user_octets_from_client{user="hello"} 37964152416 (35.36 GB)
telemt_user_octets_to_client{user="hello"} 678585637600 (631.98 GB)
telemt_user_unique_ips_current{user="hello"} 535
telemt_user_unique_ips_recent_window{user="hello"} 277
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 95769.4 (26h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3834928
telemt_connections_bad_total 340319
telemt_connections_current 523
telemt_connections_me_current 523
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 97650
telemt_upstream_connect_attempt_total 58192
telemt_upstream_connect_success_total 57478
telemt_upstream_connect_fail_total 631
telemt_upstream_connect_attempts_per_request{bucket="1"} 58109
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32291
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25000
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 187
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 631
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 6808
telemt_me_reconnect_success_total 2649
telemt_me_reader_eof_total 2599
telemt_me_idle_close_by_peer_total 2599
telemt_me_route_drop_no_conn_total 3605906
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3053648
telemt_me_endpoint_quarantine_total 734
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 737
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 37
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
telemt_desync_total 12210
telemt_desync_full_logged_total 6829
telemt_desync_suppressed_total 5381
telemt_desync_frames_bucket_total{bucket="1_2"} 2795
telemt_desync_frames_bucket_total{bucket="3_10"} 4787
telemt_desync_frames_bucket_total{bucket="gt_10"} 4628
telemt_pool_swap_total 89
telemt_pool_force_close_total 2722
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 230
telemt_me_draining_writers_reap_progress_total 38177
telemt_me_writer_removed_unexpected_total 2544
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4724
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36015
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2297
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 425
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35455
telemt_me_writer_teardown_success_total{mode="normal"} 40739
telemt_me_writer_teardown_noop_total 38178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 77021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 78231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 78839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78917
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.142140
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78917
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 230
telemt_me_refill_failed_total 166
telemt_me_writer_restored_same_endpoint_total 2336
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 183
telemt_user_connections_total{user="hello"} 3064419
telemt_user_connections_current{user="hello"} 523
telemt_user_octets_from_client{user="hello"} 40061750295 (37.31 GB)
telemt_user_octets_to_client{user="hello"} 731126975626 (680.92 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 354
telemt_user_unique_ips_recent_window{user="hello"} 167
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 170629.1 (47h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15946145
telemt_connections_bad_total 1545300
telemt_connections_current 1880
telemt_connections_me_current 1880
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 392657
telemt_upstream_connect_attempt_total 75875
telemt_upstream_connect_success_total 75778
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 75795
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37741
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36343
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1687
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2809
telemt_me_reconnect_success_total 1446
telemt_me_reader_eof_total 1389
telemt_me_idle_close_by_peer_total 1387
telemt_me_route_drop_no_conn_total 13973544
telemt_me_route_drop_channel_closed_total 144
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12704946
telemt_me_endpoint_quarantine_total 1076
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1271
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_desync_total 52407
telemt_desync_full_logged_total 16501
telemt_desync_suppressed_total 35906
telemt_desync_frames_bucket_total{bucket="1_2"} 11686
telemt_desync_frames_bucket_total{bucket="3_10"} 20422
telemt_desync_frames_bucket_total{bucket="gt_10"} 20299
telemt_pool_swap_total 184
telemt_pool_force_close_total 6219
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1013
telemt_me_draining_writers_reap_progress_total 56042
telemt_me_writer_removed_unexpected_total 1341
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4919
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51741
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 43
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5751
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 468
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49823
telemt_me_writer_teardown_success_total{mode="normal"} 56660
telemt_me_writer_teardown_noop_total 56093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 101983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 105462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 107151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 109446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 111100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 112148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 112714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 112744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 112745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 112749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 112751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 112753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 112753
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 313.689470
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 112753
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1013
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 1248
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 12705439
telemt_user_connections_current{user="hello"} 1880
telemt_user_octets_from_client{user="hello"} 185852541157 (173.09 GB)
telemt_user_octets_to_client{user="hello"} 3378549667467 (3.07 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 794
telemt_user_unique_ips_recent_window{user="hello"} 270
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 170630.6 (47h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11532625
telemt_connections_bad_total 1153402
telemt_connections_current 1514
telemt_connections_me_current 1514
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 342823
telemt_upstream_connect_attempt_total 88350
telemt_upstream_connect_success_total 87120
telemt_upstream_connect_fail_total 845
telemt_upstream_connect_attempts_per_request{bucket="1"} 87965
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47047
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36191
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 174
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3708
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 845
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 4144
telemt_me_reconnect_success_total 1724
telemt_me_reader_eof_total 1593
telemt_me_idle_close_by_peer_total 1593
telemt_me_route_drop_no_conn_total 4492116
telemt_me_route_drop_channel_closed_total 492
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8591118
telemt_me_endpoint_quarantine_total 1076
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1293
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
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
telemt_desync_total 38060
telemt_desync_full_logged_total 12818
telemt_desync_suppressed_total 25242
telemt_desync_frames_bucket_total{bucket="1_2"} 9381
telemt_desync_frames_bucket_total{bucket="3_10"} 14652
telemt_desync_frames_bucket_total{bucket="gt_10"} 14027
telemt_pool_swap_total 181
telemt_pool_force_close_total 5608
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 702
telemt_me_draining_writers_reap_progress_total 54468
telemt_me_writer_removed_unexpected_total 1630
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5025
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50920
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5105
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 503
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48860
telemt_me_writer_teardown_success_total{mode="normal"} 55945
telemt_me_writer_teardown_noop_total 54493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 103796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 106938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 108073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 109259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 110014
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 110353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 110428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 110430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 110436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 110438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 110438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 110438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 110438
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 103.660498
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 110438
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 702
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 1474
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 140
telemt_user_connections_total{user="hello"} 8529253
telemt_user_connections_current{user="hello"} 1514
telemt_user_octets_from_client{user="hello"} 214435673521 (199.71 GB)
telemt_user_octets_to_client{user="hello"} 3854512215902 (3.51 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 584
telemt_user_unique_ips_recent_window{user="hello"} 188
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 170597.9 (47h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10815610
telemt_connections_bad_total 935117
telemt_connections_current 1038
telemt_connections_me_current 1038
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 343812
telemt_upstream_connect_attempt_total 73475
telemt_upstream_connect_success_total 72345
telemt_upstream_connect_fail_total 185
telemt_upstream_connect_attempts_per_request{bucket="1"} 72530
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33933
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34623
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1613
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2176
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 185
telemt_me_keepalive_timeout_total 1385
telemt_me_reconnect_attempts_total 5006
telemt_me_reconnect_success_total 2015
telemt_me_reader_eof_total 1762
telemt_me_idle_close_by_peer_total 1761
telemt_me_route_drop_no_conn_total 5261281
telemt_me_route_drop_channel_closed_total 375
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8179142
telemt_me_endpoint_quarantine_total 1158
telemt_me_single_endpoint_outage_enter_total 34
telemt_me_single_endpoint_outage_exit_total 34
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 29
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1251
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 61
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
telemt_desync_total 37520
telemt_desync_full_logged_total 12418
telemt_desync_suppressed_total 25102
telemt_desync_frames_bucket_total{bucket="1_2"} 9489
telemt_desync_frames_bucket_total{bucket="3_10"} 14348
telemt_desync_frames_bucket_total{bucket="gt_10"} 13683
telemt_pool_swap_total 179
telemt_pool_force_close_total 5553
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 713
telemt_me_draining_writers_reap_progress_total 54571
telemt_me_writer_removed_unexpected_total 1904
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5484
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50910
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5002
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 551
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49018
telemt_me_writer_teardown_success_total{mode="normal"} 56394
telemt_me_writer_teardown_noop_total 54642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 105299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 107956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 108899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 109960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 110555
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 110769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 110897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 110928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 110936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 110949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 110982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 110985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 111036
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3173.978504
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 111036
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 713
telemt_me_refill_failed_total 159
telemt_me_writer_restored_same_endpoint_total 1735
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 156
telemt_user_connections_total{user="hello"} 8171408
telemt_user_connections_current{user="hello"} 1038
telemt_user_octets_from_client{user="hello"} 190653764573 (177.56 GB)
telemt_user_octets_to_client{user="hello"} 3400138355389 (3.09 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 421
telemt_user_unique_ips_recent_window{user="hello"} 151
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 40874.7 (11h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10811987
telemt_connections_bad_total 657883
telemt_connections_current 1964
telemt_connections_me_current 1964
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 233087
telemt_upstream_connect_attempt_total 45208
telemt_upstream_connect_success_total 42945
telemt_upstream_connect_fail_total 1553
telemt_upstream_connect_attempts_per_request{bucket="1"} 44498
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21927
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13597
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1460
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5961
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1553
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6536
telemt_me_reconnect_success_total 908
telemt_me_reader_eof_total 566
telemt_me_idle_close_by_peer_total 566
telemt_me_route_drop_no_conn_total 25194402
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8979810
telemt_me_endpoint_quarantine_total 261
telemt_me_single_endpoint_outage_enter_total 65
telemt_me_single_endpoint_outage_exit_total 65
telemt_me_single_endpoint_outage_reconnect_attempt_total 117
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 117
telemt_me_single_endpoint_shadow_rotate_total 320
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
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
telemt_desync_total 14587
telemt_desync_full_logged_total 3852
telemt_desync_suppressed_total 10735
telemt_desync_frames_bucket_total{bucket="1_2"} 2698
telemt_desync_frames_bucket_total{bucket="3_10"} 5927
telemt_desync_frames_bucket_total{bucket="gt_10"} 5962
telemt_pool_swap_total 41
telemt_pool_force_close_total 1507
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 434
telemt_me_draining_writers_reap_progress_total 11676
telemt_me_writer_removed_unexpected_total 810
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1748
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 10687
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1206
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 301
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 10169
telemt_me_writer_teardown_success_total{mode="normal"} 12435
telemt_me_writer_teardown_noop_total 11695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 20618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 22183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 22805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 23603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 23956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 24074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 24130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 24130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 24130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 24130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 24130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 24130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 24130
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 50.375992
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 24130
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 434
telemt_me_refill_failed_total 311
telemt_me_writer_restored_same_endpoint_total 610
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 195
telemt_user_connections_total{user="hello"} 9001907
telemt_user_connections_current{user="hello"} 1964
telemt_user_octets_from_client{user="hello"} 82232765207 (76.59 GB)
telemt_user_octets_to_client{user="hello"} 489100985279 (455.51 GB)
telemt_user_msgs_from_client{user="hello"} 58278
telemt_user_msgs_to_client{user="hello"} 46361
telemt_user_unique_ips_current{user="hello"} 735
telemt_user_unique_ips_recent_window{user="hello"} 249
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 170601.3 (47h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10699241
telemt_connections_bad_total 903284
telemt_connections_current 1535
telemt_connections_me_current 1535
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 235453
telemt_upstream_connect_attempt_total 102888
telemt_upstream_connect_success_total 101803
telemt_upstream_connect_fail_total 926
telemt_upstream_connect_attempts_per_request{bucket="1"} 102729
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61946
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38282
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1337
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 926
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72382
telemt_me_reconnect_success_total 2824
telemt_me_reader_eof_total 2514
telemt_me_idle_close_by_peer_total 2512
telemt_me_route_drop_no_conn_total 5195132
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8450382
telemt_me_endpoint_quarantine_total 1126
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 41
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 41
telemt_me_single_endpoint_shadow_rotate_total 1275
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
telemt_me_writers_active_current 49
telemt_desync_total 44967
telemt_desync_full_logged_total 15309
telemt_desync_suppressed_total 29658
telemt_desync_frames_bucket_total{bucket="1_2"} 9124
telemt_desync_frames_bucket_total{bucket="3_10"} 17222
telemt_desync_frames_bucket_total{bucket="gt_10"} 18621
telemt_pool_swap_total 174
telemt_pool_force_close_total 5198
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 639
telemt_me_draining_writers_reap_progress_total 58446
telemt_me_writer_removed_unexpected_total 2552
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6225
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54799
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4471
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 727
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 53248
telemt_me_writer_teardown_success_total{mode="normal"} 61024
telemt_me_writer_teardown_noop_total 58447
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 117374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 118736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 119154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 119427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 119461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 119464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 119464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 119467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 119471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 119471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 119471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 119471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 119471
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.024825
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 119471
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 639
telemt_me_refill_failed_total 4285
telemt_me_writer_restored_same_endpoint_total 2373
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 131
telemt_user_connections_total{user="hello"} 8453652
telemt_user_connections_current{user="hello"} 1535
telemt_user_octets_from_client{user="hello"} 191635480733 (178.47 GB)
telemt_user_octets_to_client{user="hello"} 3212269276000 (2.92 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 592
telemt_user_unique_ips_recent_window{user="hello"} 170
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 107437.4 (29h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11283669
telemt_connections_bad_total 450470
telemt_connections_current 1163
telemt_connections_me_current 1163
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4646623
telemt_upstream_connect_attempt_total 50998
telemt_upstream_connect_success_total 50617
telemt_upstream_connect_fail_total 372
telemt_upstream_connect_attempts_per_request{bucket="1"} 50989
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27780
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22640
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 197
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 372
telemt_me_reconnect_attempts_total 48490
telemt_me_reconnect_success_total 1672
telemt_me_reader_eof_total 1329
telemt_me_idle_close_by_peer_total 1328
telemt_me_route_drop_no_conn_total 4034818
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5432392
telemt_me_endpoint_quarantine_total 696
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 812
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
telemt_me_writers_active_current 42
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 30492
telemt_desync_full_logged_total 10334
telemt_desync_suppressed_total 20158
telemt_desync_frames_bucket_total{bucket="1_2"} 6083
telemt_desync_frames_bucket_total{bucket="3_10"} 12060
telemt_desync_frames_bucket_total{bucket="gt_10"} 12349
telemt_pool_swap_total 113
telemt_pool_force_close_total 3456
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 351
telemt_me_draining_writers_reap_progress_total 37414
telemt_me_writer_removed_unexpected_total 1389
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3318
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35519
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3016
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 440
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33958
telemt_me_writer_teardown_success_total{mode="normal"} 38837
telemt_me_writer_teardown_noop_total 37421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 75006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 75727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 76031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 76258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 76258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 76258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 76258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 76258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 76258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 76258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 76258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 76258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 76258
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.474706
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 76258
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 351
telemt_me_refill_failed_total 2721
telemt_me_writer_restored_same_endpoint_total 1488
telemt_me_writer_restored_fallback_total 19
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5425248
telemt_user_connections_current{user="hello"} 1163
telemt_user_octets_from_client{user="hello"} 117034109364 (109.00 GB)
telemt_user_octets_to_client{user="hello"} 2077977745162 (1.89 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 483
telemt_user_unique_ips_recent_window{user="hello"} 184
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 88408.5 (24h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1328931
telemt_connections_bad_total 29255
telemt_connections_current 953
telemt_connections_me_current 953
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 24980
telemt_upstream_connect_attempt_total 41958
telemt_upstream_connect_success_total 41832
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 41931
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18861
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22259
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 712
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 1937
telemt_me_reconnect_success_total 807
telemt_me_reader_eof_total 785
telemt_me_idle_close_by_peer_total 785
telemt_me_route_drop_no_conn_total 464917
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1179977
telemt_me_endpoint_quarantine_total 736
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 728
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_desync_total 7001
telemt_desync_full_logged_total 2171
telemt_desync_suppressed_total 4830
telemt_desync_frames_bucket_total{bucket="1_2"} 1551
telemt_desync_frames_bucket_total{bucket="3_10"} 2765
telemt_desync_frames_bucket_total{bucket="gt_10"} 2685
telemt_pool_swap_total 95
telemt_pool_force_close_total 2460
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 142
telemt_me_draining_writers_reap_progress_total 34945
telemt_me_writer_removed_unexpected_total 757
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2757
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32976
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2375
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 85
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32485
telemt_me_writer_teardown_success_total{mode="normal"} 35733
telemt_me_writer_teardown_noop_total 34949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 69885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 70468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 70645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 70682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 70682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 70682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 70682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 70682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 70682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 70682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 70682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 70682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 70682
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.374420
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 70682
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 142
telemt_me_refill_failed_total 62
telemt_me_writer_restored_same_endpoint_total 684
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 1176063
telemt_user_connections_current{user="hello"} 953
telemt_user_octets_from_client{user="hello"} 22748576953 (21.19 GB)
telemt_user_octets_to_client{user="hello"} 498129979703 (463.92 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 335
telemt_user_unique_ips_recent_window{user="hello"} 338
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 170605.7 (47h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13012543
telemt_connections_bad_total 1517017
telemt_connections_current 1535
telemt_connections_me_current 1535
telemt_handshake_timeouts_total 373135
telemt_upstream_connect_attempt_total 64391
telemt_upstream_connect_success_total 64059
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 64256
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31690
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32269
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2527
telemt_me_reconnect_success_total 1320
telemt_me_reader_eof_total 1285
telemt_me_idle_close_by_peer_total 1285
telemt_me_route_drop_no_conn_total 4417288
telemt_me_route_drop_channel_closed_total 122
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9849495
telemt_me_endpoint_quarantine_total 1142
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1278
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
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
telemt_desync_total 40774
telemt_desync_full_logged_total 13293
telemt_desync_suppressed_total 27481
telemt_desync_frames_bucket_total{bucket="1_2"} 9728
telemt_desync_frames_bucket_total{bucket="3_10"} 15051
telemt_desync_frames_bucket_total{bucket="gt_10"} 15995
telemt_pool_swap_total 189
telemt_pool_force_close_total 5201
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 652
telemt_me_draining_writers_reap_progress_total 58009
telemt_me_writer_removed_unexpected_total 1236
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4738
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54546
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5027
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52808
telemt_me_writer_teardown_success_total{mode="normal"} 59284
telemt_me_writer_teardown_noop_total 58011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 114758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 116407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 116786
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 117162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 117282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 117295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 117295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 117295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 117295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 117295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 117295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 117295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 117295
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.443140
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 117295
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 652
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 1153
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 9817180
telemt_user_connections_current{user="hello"} 1535
telemt_user_octets_from_client{user="hello"} 191988792924 (178.80 GB)
telemt_user_octets_to_client{user="hello"} 4337390287692 (3.94 TB)
telemt_user_unique_ips_current{user="hello"} 556
telemt_user_unique_ips_recent_window{user="hello"} 171
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 170602.5 (47h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11316603
telemt_connections_bad_total 1282283
telemt_connections_current 1463
telemt_connections_me_current 1463
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 297572
telemt_upstream_connect_attempt_total 90856
telemt_upstream_connect_success_total 90036
telemt_upstream_connect_fail_total 614
telemt_upstream_connect_attempts_per_request{bucket="1"} 90650
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49228
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37830
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2065
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 614
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 9759
telemt_me_reconnect_success_total 2340
telemt_me_reader_eof_total 2186
telemt_me_idle_close_by_peer_total 2185
telemt_me_seq_mismatch_total 78
telemt_me_route_drop_no_conn_total 5591799
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8748067
telemt_me_endpoint_quarantine_total 1304
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 46
telemt_me_single_endpoint_outage_exit_total 46
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1276
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 53
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
telemt_desync_total 39957
telemt_desync_full_logged_total 12912
telemt_desync_suppressed_total 27045
telemt_desync_frames_bucket_total{bucket="1_2"} 9975
telemt_desync_frames_bucket_total{bucket="3_10"} 14855
telemt_desync_frames_bucket_total{bucket="gt_10"} 15127
telemt_pool_swap_total 179
telemt_pool_force_close_total 4997
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 635
telemt_me_draining_writers_reap_progress_total 57832
telemt_me_writer_removed_unexpected_total 2219
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6073
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54052
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4526
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52835
telemt_me_writer_teardown_success_total{mode="normal"} 60125
telemt_me_writer_teardown_noop_total 57837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 115323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 117057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 117593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 117912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 117962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 117962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 117962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 117962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 117962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 117962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 117962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 117962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 117962
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.170613
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 117962
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 635
telemt_me_refill_failed_total 383
telemt_me_writer_restored_same_endpoint_total 1909
telemt_me_writer_restored_fallback_total 108
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 202
telemt_user_connections_total{user="hello"} 8753629
telemt_user_connections_current{user="hello"} 1463
telemt_user_octets_from_client{user="hello"} 155046745033 (144.40 GB)
telemt_user_octets_to_client{user="hello"} 3383861506871 (3.08 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 534
telemt_user_unique_ips_recent_window{user="hello"} 181
```