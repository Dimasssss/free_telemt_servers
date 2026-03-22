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

# Server Metrics 2026-03-22 15:28:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 66124.5 (18h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2304828
telemt_connections_bad_total 124276
telemt_connections_current 1684
telemt_connections_me_current 1684
telemt_handshake_timeouts_total 85850
telemt_upstream_connect_attempt_total 24499
telemt_upstream_connect_success_total 24498
telemt_upstream_connect_attempts_per_request{bucket="1"} 24498
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8535
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15896
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 54
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 1009
telemt_me_reconnect_success_total 417
telemt_me_reader_eof_total 420
telemt_me_idle_close_by_peer_total 420
telemt_me_route_drop_no_conn_total 1853411
telemt_me_route_drop_channel_closed_total 746
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1955844
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 453
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 521
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 21
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
telemt_desync_total 9701
telemt_desync_full_logged_total 2999
telemt_desync_suppressed_total 6702
telemt_desync_frames_bucket_total{bucket="1_2"} 2628
telemt_desync_frames_bucket_total{bucket="3_10"} 3637
telemt_desync_frames_bucket_total{bucket="gt_10"} 3436
telemt_pool_swap_total 73
telemt_pool_force_close_total 2247
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 413
telemt_me_draining_writers_reap_progress_total 22384
telemt_me_writer_removed_unexpected_total 407
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1621
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20971
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2200
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 47
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20137
telemt_me_writer_teardown_success_total{mode="normal"} 22592
telemt_me_writer_teardown_noop_total 22390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44982
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 196.537580
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44982
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 413
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 1952651
telemt_user_connections_current{user="hello"} 1684
telemt_user_octets_from_client{user="hello"} 29520286936 (27.49 GB)
telemt_user_octets_to_client{user="hello"} 525508761624 (489.42 GB)
telemt_user_unique_ips_current{user="hello"} 645
telemt_user_unique_ips_recent_window{user="hello"} 260
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 79490.7 (22h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3526282
telemt_connections_bad_total 320559
telemt_connections_current 1129
telemt_connections_me_current 1129
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 84487
telemt_upstream_connect_attempt_total 50232
telemt_upstream_connect_success_total 49617
telemt_upstream_connect_fail_total 542
telemt_upstream_connect_attempts_per_request{bucket="1"} 50159
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29176
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20278
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 163
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 542
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 5724
telemt_me_reconnect_success_total 1992
telemt_me_reader_eof_total 1921
telemt_me_idle_close_by_peer_total 1921
telemt_me_route_drop_no_conn_total 3509911
telemt_me_route_drop_channel_closed_total 35
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2794750
telemt_me_endpoint_quarantine_total 643
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 616
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 34
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
telemt_me_writers_active_current 86
telemt_desync_total 10785
telemt_desync_full_logged_total 5985
telemt_desync_suppressed_total 4800
telemt_desync_frames_bucket_total{bucket="1_2"} 2532
telemt_desync_frames_bucket_total{bucket="3_10"} 4257
telemt_desync_frames_bucket_total{bucket="gt_10"} 3996
telemt_pool_swap_total 75
telemt_pool_force_close_total 2228
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 187
telemt_me_draining_writers_reap_progress_total 31452
telemt_me_writer_removed_unexpected_total 1877
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3679
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29653
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1910
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 318
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29224
telemt_me_writer_teardown_success_total{mode="normal"} 33332
telemt_me_writer_teardown_noop_total 31452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 63209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 64225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 64484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 64749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64784
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.578751
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64784
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 187
telemt_me_refill_failed_total 146
telemt_me_writer_restored_same_endpoint_total 1702
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 35
telemt_me_writer_removed_unexpected_minus_restored_total 151
telemt_user_connections_total{user="hello"} 2806108
telemt_user_connections_current{user="hello"} 1129
telemt_user_octets_from_client{user="hello"} 34307114799 (31.95 GB)
telemt_user_octets_to_client{user="hello"} 611333563650 (569.35 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 687
telemt_user_unique_ips_recent_window{user="hello"} 213
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 154350.6 (42h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15134244
telemt_connections_bad_total 1388524
telemt_connections_current 1966
telemt_connections_me_current 1966
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 367375
telemt_upstream_connect_attempt_total 70057
telemt_upstream_connect_success_total 69962
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 69979
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35334
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32957
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1664
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2585
telemt_me_reconnect_success_total 1333
telemt_me_reader_eof_total 1270
telemt_me_idle_close_by_peer_total 1269
telemt_me_route_drop_no_conn_total 13736167
telemt_me_route_drop_channel_closed_total 134
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12110734
telemt_me_endpoint_quarantine_total 974
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1151
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_desync_total 48954
telemt_desync_full_logged_total 15362
telemt_desync_suppressed_total 33592
telemt_desync_frames_bucket_total{bucket="1_2"} 11004
telemt_desync_frames_bucket_total{bucket="3_10"} 19147
telemt_desync_frames_bucket_total{bucket="gt_10"} 18803
telemt_pool_swap_total 166
telemt_pool_force_close_total 5663
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 924
telemt_me_draining_writers_reap_progress_total 50769
telemt_me_writer_removed_unexpected_total 1226
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4424
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46876
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5204
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 459
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45106
telemt_me_writer_teardown_success_total{mode="normal"} 51300
telemt_me_writer_teardown_noop_total 50819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 92196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 95419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 96987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 99105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 100616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 101551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 102080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 102110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 102111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 102115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 102117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 102119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 102119
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 291.561455
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 102119
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 924
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 1144
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 12112211
telemt_user_connections_current{user="hello"} 1966
telemt_user_octets_from_client{user="hello"} 169964748861 (158.29 GB)
telemt_user_octets_to_client{user="hello"} 3111433412827 (2.83 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 799
telemt_user_unique_ips_recent_window{user="hello"} 275
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 154352.0 (42h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10912816
telemt_connections_bad_total 1052614
telemt_connections_current 1451
telemt_connections_me_current 1451
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 322697
telemt_upstream_connect_attempt_total 82240
telemt_upstream_connect_success_total 81088
telemt_upstream_connect_fail_total 828
telemt_upstream_connect_attempts_per_request{bucket="1"} 81916
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44381
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32858
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3692
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 828
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3892
telemt_me_reconnect_success_total 1575
telemt_me_reader_eof_total 1442
telemt_me_idle_close_by_peer_total 1442
telemt_me_route_drop_no_conn_total 4326140
telemt_me_route_drop_channel_closed_total 477
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8146527
telemt_me_endpoint_quarantine_total 972
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1171
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_me_writers_active_current 46
telemt_desync_total 36149
telemt_desync_full_logged_total 12137
telemt_desync_suppressed_total 24012
telemt_desync_frames_bucket_total{bucket="1_2"} 8866
telemt_desync_frames_bucket_total{bucket="3_10"} 13918
telemt_desync_frames_bucket_total{bucket="gt_10"} 13365
telemt_pool_swap_total 164
telemt_pool_force_close_total 5097
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 658
telemt_me_draining_writers_reap_progress_total 49065
telemt_me_writer_removed_unexpected_total 1474
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4537
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45859
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4625
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 472
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43968
telemt_me_writer_teardown_success_total{mode="normal"} 50396
telemt_me_writer_teardown_noop_total 49083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 93280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 96185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 97257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 98349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 99063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 99394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 99469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 99471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 99477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 99479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 99479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 99479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 99479
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 99.057712
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 99479
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 658
telemt_me_refill_failed_total 125
telemt_me_writer_restored_same_endpoint_total 1338
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 122
telemt_user_connections_total{user="hello"} 8085373
telemt_user_connections_current{user="hello"} 1451
telemt_user_octets_from_client{user="hello"} 203093980725 (189.15 GB)
telemt_user_octets_to_client{user="hello"} 3644533196398 (3.31 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 579
telemt_user_unique_ips_recent_window{user="hello"} 190
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 154316.1 (42h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10344935
telemt_connections_bad_total 885323
telemt_connections_current 1330
telemt_connections_me_current 1330
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 329946
telemt_upstream_connect_attempt_total 67466
telemt_upstream_connect_success_total 66540
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 66722
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31867
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31374
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1243
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2056
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4619
telemt_me_reconnect_success_total 1862
telemt_me_reader_eof_total 1619
telemt_me_idle_close_by_peer_total 1618
telemt_me_route_drop_no_conn_total 5099355
telemt_me_route_drop_channel_closed_total 353
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7811463
telemt_me_endpoint_quarantine_total 1059
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 31
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 31
telemt_me_single_endpoint_shadow_rotate_total 1134
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
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
telemt_desync_total 35799
telemt_desync_full_logged_total 11866
telemt_desync_suppressed_total 23933
telemt_desync_frames_bucket_total{bucket="1_2"} 9055
telemt_desync_frames_bucket_total{bucket="3_10"} 13673
telemt_desync_frames_bucket_total{bucket="gt_10"} 13071
telemt_pool_swap_total 161
telemt_pool_force_close_total 5048
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 682
telemt_me_draining_writers_reap_progress_total 49527
telemt_me_writer_removed_unexpected_total 1759
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4973
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46225
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4511
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 537
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44479
telemt_me_writer_teardown_success_total{mode="normal"} 51198
telemt_me_writer_teardown_noop_total 49598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 95406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 97862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 98755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 99753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 100322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 100532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 100660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 100688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 100696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 100709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 100742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 100745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 100796
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3169.941149
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 100796
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 682
telemt_me_refill_failed_total 146
telemt_me_writer_restored_same_endpoint_total 1613
telemt_me_writer_restored_fallback_total 8
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 138
telemt_user_connections_total{user="hello"} 7804551
telemt_user_connections_current{user="hello"} 1330
telemt_user_octets_from_client{user="hello"} 180247958737 (167.87 GB)
telemt_user_octets_to_client{user="hello"} 3241333868729 (2.95 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 521
telemt_user_unique_ips_recent_window{user="hello"} 179
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 24596.9 (6h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9954051
telemt_connections_bad_total 609423
telemt_connections_current 2148
telemt_connections_me_current 2148
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 166461
telemt_upstream_connect_attempt_total 34454
telemt_upstream_connect_success_total 32721
telemt_upstream_connect_fail_total 1245
telemt_upstream_connect_attempts_per_request{bucket="1"} 33966
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17889
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8558
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 988
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5286
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1245
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 5689
telemt_me_reconnect_success_total 668
telemt_me_reader_eof_total 412
telemt_me_idle_close_by_peer_total 412
telemt_me_route_drop_no_conn_total 24829032
telemt_me_route_drop_channel_closed_total 39
telemt_me_route_drop_queue_full_total 26
telemt_me_route_drop_queue_full_profile_total{profile="high"} 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8298551
telemt_me_endpoint_quarantine_total 157
telemt_me_single_endpoint_outage_enter_total 47
telemt_me_single_endpoint_outage_exit_total 47
telemt_me_single_endpoint_outage_reconnect_attempt_total 81
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 81
telemt_me_single_endpoint_shadow_rotate_total 193
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 19
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
telemt_desync_total 12570
telemt_desync_full_logged_total 3223
telemt_desync_suppressed_total 9347
telemt_desync_frames_bucket_total{bucket="1_2"} 2168
telemt_desync_frames_bucket_total{bucket="3_10"} 5108
telemt_desync_frames_bucket_total{bucket="gt_10"} 5294
telemt_pool_swap_total 23
telemt_pool_force_close_total 953
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 355
telemt_me_draining_writers_reap_progress_total 6586
telemt_me_writer_removed_unexpected_total 574
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1157
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5967
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 679
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 274
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5633
telemt_me_writer_teardown_success_total{mode="normal"} 7124
telemt_me_writer_teardown_noop_total 6591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 11122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 12393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 12844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 13367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 13614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 13707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 13715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 13715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 13715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 13715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 13715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 13715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 13715
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 31.163538
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 13715
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 355
telemt_me_refill_failed_total 285
telemt_me_writer_restored_same_endpoint_total 455
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 8316870
telemt_user_connections_current{user="hello"} 2148
telemt_user_octets_from_client{user="hello"} 54174618750 (50.45 GB)
telemt_user_octets_to_client{user="hello"} 252949517100 (235.58 GB)
telemt_user_msgs_from_client{user="hello"} 48912
telemt_user_msgs_to_client{user="hello"} 39981
telemt_user_unique_ips_current{user="hello"} 774
telemt_user_unique_ips_recent_window{user="hello"} 304
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 154322.7 (42h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10089953
telemt_connections_bad_total 840055
telemt_connections_current 1854
telemt_connections_me_current 1854
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 221660
telemt_upstream_connect_attempt_total 92290
telemt_upstream_connect_success_total 91335
telemt_upstream_connect_fail_total 812
telemt_upstream_connect_attempts_per_request{bucket="1"} 92147
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56182
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33679
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1266
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 812
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71588
telemt_me_reconnect_success_total 2563
telemt_me_reader_eof_total 2275
telemt_me_idle_close_by_peer_total 2274
telemt_me_route_drop_no_conn_total 5023791
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7966733
telemt_me_endpoint_quarantine_total 1037
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 35
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1151
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 47
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
telemt_me_writers_active_current 46
telemt_desync_total 41248
telemt_desync_full_logged_total 14103
telemt_desync_suppressed_total 27145
telemt_desync_frames_bucket_total{bucket="1_2"} 8384
telemt_desync_frames_bucket_total{bucket="3_10"} 16009
telemt_desync_frames_bucket_total{bucket="gt_10"} 16855
telemt_pool_swap_total 157
telemt_pool_force_close_total 4704
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 576
telemt_me_draining_writers_reap_progress_total 52568
telemt_me_writer_removed_unexpected_total 2320
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5613
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49294
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4025
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 679
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47864
telemt_me_writer_teardown_success_total{mode="normal"} 54907
telemt_me_writer_teardown_noop_total 52569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 105519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 106784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 107162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 107432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 107466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 107469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 107469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 107472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 107476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 107476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 107476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 107476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 107476
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.330424
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 107476
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 576
telemt_me_refill_failed_total 4258
telemt_me_writer_restored_same_endpoint_total 2159
telemt_me_writer_restored_fallback_total 43
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7358
telemt_me_writer_removed_unexpected_minus_restored_total 118
telemt_user_connections_total{user="hello"} 7966950
telemt_user_connections_current{user="hello"} 1854
telemt_user_octets_from_client{user="hello"} 180762622411 (168.35 GB)
telemt_user_octets_to_client{user="hello"} 2994401310893 (2.72 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 687
telemt_user_unique_ips_recent_window{user="hello"} 240
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 91158.8 (25h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10480069
telemt_connections_bad_total 384475
telemt_connections_current 1344
telemt_connections_me_current 1344
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4424671
telemt_upstream_connect_attempt_total 44143
telemt_upstream_connect_success_total 43818
telemt_upstream_connect_fail_total 316
telemt_upstream_connect_attempts_per_request{bucket="1"} 44134
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24818
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18857
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 143
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 316
telemt_me_reconnect_attempts_total 48029
telemt_me_reconnect_success_total 1493
telemt_me_reader_eof_total 1157
telemt_me_idle_close_by_peer_total 1156
telemt_me_route_drop_no_conn_total 3882108
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5021353
telemt_me_endpoint_quarantine_total 598
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 687
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 21
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
telemt_desync_total 27396
telemt_desync_full_logged_total 9247
telemt_desync_suppressed_total 18149
telemt_desync_frames_bucket_total{bucket="1_2"} 5527
telemt_desync_frames_bucket_total{bucket="3_10"} 10833
telemt_desync_frames_bucket_total{bucket="gt_10"} 11036
telemt_pool_swap_total 96
telemt_pool_force_close_total 2981
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 309
telemt_me_draining_writers_reap_progress_total 31301
telemt_me_writer_removed_unexpected_total 1220
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2837
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29714
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2562
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 419
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28320
telemt_me_writer_teardown_success_total{mode="normal"} 32551
telemt_me_writer_teardown_noop_total 31308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 63635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 63859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 63859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 63859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 63859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 63859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 63859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 63859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 63859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 63859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 63859
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.608447
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 63859
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 309
telemt_me_refill_failed_total 2705
telemt_me_writer_restored_same_endpoint_total 1328
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 5015036
telemt_user_connections_current{user="hello"} 1344
telemt_user_octets_from_client{user="hello"} 108352478388 (100.91 GB)
telemt_user_octets_to_client{user="hello"} 1887674193858 (1.72 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 516
telemt_user_unique_ips_recent_window{user="hello"} 215
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 72130.9 (20h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 927597
telemt_connections_bad_total 12028
telemt_connections_current 1090
telemt_connections_me_current 1090
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 18165
telemt_upstream_connect_attempt_total 35794
telemt_upstream_connect_success_total 35704
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 35778
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16242
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18969
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 493
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_reconnect_attempts_total 1615
telemt_me_reconnect_success_total 683
telemt_me_reader_eof_total 658
telemt_me_idle_close_by_peer_total 658
telemt_me_route_drop_no_conn_total 318209
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 825601
telemt_me_endpoint_quarantine_total 634
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 598
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 13
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
telemt_desync_total 4550
telemt_desync_full_logged_total 1384
telemt_desync_suppressed_total 3166
telemt_desync_frames_bucket_total{bucket="1_2"} 1070
telemt_desync_frames_bucket_total{bucket="3_10"} 1803
telemt_desync_frames_bucket_total{bucket="gt_10"} 1677
telemt_pool_swap_total 77
telemt_pool_force_close_total 1908
telemt_me_writer_close_signal_drop_total 109
telemt_me_draining_writers_reap_progress_total 29541
telemt_me_writer_removed_unexpected_total 636
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2277
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27924
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1830
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 78
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27633
telemt_me_writer_teardown_success_total{mode="normal"} 30201
telemt_me_writer_teardown_noop_total 29543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59744
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.467474
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59744
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 109
telemt_me_refill_failed_total 51
telemt_me_writer_restored_same_endpoint_total 582
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 826678
telemt_user_connections_current{user="hello"} 1090
telemt_user_octets_from_client{user="hello"} 15098990629 (14.06 GB)
telemt_user_octets_to_client{user="hello"} 376931145443 (351.04 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 414
telemt_user_unique_ips_recent_window{user="hello"} 165
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 154327.2 (42h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12379787
telemt_connections_bad_total 1439868
telemt_connections_current 1937
telemt_connections_me_current 1937
telemt_handshake_timeouts_total 339044
telemt_upstream_connect_attempt_total 57766
telemt_upstream_connect_success_total 57539
telemt_upstream_connect_fail_total 177
telemt_upstream_connect_attempts_per_request{bucket="1"} 57716
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28350
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29125
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 177
telemt_me_reconnect_attempts_total 2257
telemt_me_reconnect_success_total 1200
telemt_me_reader_eof_total 1165
telemt_me_idle_close_by_peer_total 1165
telemt_me_route_drop_no_conn_total 4133098
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 36
telemt_me_route_drop_queue_full_profile_total{profile="high"} 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9351818
telemt_me_endpoint_quarantine_total 1045
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1152
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_desync_total 38323
telemt_desync_full_logged_total 12518
telemt_desync_suppressed_total 25805
telemt_desync_frames_bucket_total{bucket="1_2"} 9113
telemt_desync_frames_bucket_total{bucket="3_10"} 14205
telemt_desync_frames_bucket_total{bucket="gt_10"} 15005
telemt_pool_swap_total 171
telemt_pool_force_close_total 4736
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 609
telemt_me_draining_writers_reap_progress_total 52037
telemt_me_writer_removed_unexpected_total 1119
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4277
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48911
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4563
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 173
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47301
telemt_me_writer_teardown_success_total{mode="normal"} 53188
telemt_me_writer_teardown_noop_total 52039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 102888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 104447
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 104780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 105094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 105214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 105227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 105227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 105227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 105227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 105227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 105227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 105227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 105227
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.877804
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 105227
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 609
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 1050
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 9321192
telemt_user_connections_current{user="hello"} 1937
telemt_user_octets_from_client{user="hello"} 180831769256 (168.41 GB)
telemt_user_octets_to_client{user="hello"} 4118432209040 (3.75 TB)
telemt_user_unique_ips_current{user="hello"} 717
telemt_user_unique_ips_recent_window{user="hello"} 237
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 154323.8 (42h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10720554
telemt_connections_bad_total 1196945
telemt_connections_current 1525
telemt_connections_me_current 1525
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 276846
telemt_upstream_connect_attempt_total 83591
telemt_upstream_connect_success_total 82967
telemt_upstream_connect_fail_total 540
telemt_upstream_connect_attempts_per_request{bucket="1"} 83507
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45702
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34328
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2028
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 540
telemt_me_reconnect_attempts_total 8829
telemt_me_reconnect_success_total 2030
telemt_me_reader_eof_total 1897
telemt_me_idle_close_by_peer_total 1897
telemt_me_seq_mismatch_total 72
telemt_me_route_drop_no_conn_total 5381326
telemt_me_route_drop_channel_closed_total 344
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8284764
telemt_me_endpoint_quarantine_total 1171
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1157
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 47
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
telemt_desync_total 37949
telemt_desync_full_logged_total 12250
telemt_desync_suppressed_total 25699
telemt_desync_frames_bucket_total{bucket="1_2"} 9443
telemt_desync_frames_bucket_total{bucket="3_10"} 14149
telemt_desync_frames_bucket_total{bucket="gt_10"} 14357
telemt_pool_swap_total 163
telemt_pool_force_close_total 4582
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 597
telemt_me_draining_writers_reap_progress_total 51518
telemt_me_writer_removed_unexpected_total 1922
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5373
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48134
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4143
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 439
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46936
telemt_me_writer_teardown_success_total{mode="normal"} 53507
telemt_me_writer_teardown_noop_total 51523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 102547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 104171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 104668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 104980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 105030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 105030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 105030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 105030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 105030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 105030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 105030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 105030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 105030
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.318183
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 105030
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 597
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 1653
telemt_me_writer_restored_fallback_total 98
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 8290846
telemt_user_connections_current{user="hello"} 1525
telemt_user_octets_from_client{user="hello"} 146140884501 (136.10 GB)
telemt_user_octets_to_client{user="hello"} 3163224671503 (2.88 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 586
telemt_user_unique_ips_recent_window{user="hello"} 182
```