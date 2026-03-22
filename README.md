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

# Server Metrics 2026-03-22 18:17:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 76234.9 (21h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2773875
telemt_connections_bad_total 163175
telemt_connections_current 1460
telemt_connections_me_current 1460
telemt_handshake_timeouts_total 94555
telemt_upstream_connect_attempt_total 27984
telemt_upstream_connect_success_total 27983
telemt_upstream_connect_attempts_per_request{bucket="1"} 27983
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9706
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18185
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 67
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 1130
telemt_me_reconnect_success_total 480
telemt_me_reader_eof_total 482
telemt_me_idle_close_by_peer_total 482
telemt_me_route_drop_no_conn_total 2299255
telemt_me_route_drop_channel_closed_total 953
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2358995
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 515
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 595
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 23
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
telemt_desync_total 10743
telemt_desync_full_logged_total 3402
telemt_desync_suppressed_total 7341
telemt_desync_frames_bucket_total{bucket="1_2"} 2881
telemt_desync_frames_bucket_total{bucket="3_10"} 3985
telemt_desync_frames_bucket_total{bucket="gt_10"} 3877
telemt_pool_swap_total 84
telemt_pool_force_close_total 2610
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 542
telemt_me_draining_writers_reap_progress_total 25563
telemt_me_writer_removed_unexpected_total 468
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1873
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23916
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2557
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22953
telemt_me_writer_teardown_success_total{mode="normal"} 25789
telemt_me_writer_teardown_noop_total 25573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 51066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 51358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 51362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 51362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 51362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 51362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 51362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 51362
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 257.651627
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 51362
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 542
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 425
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 2355126
telemt_user_connections_current{user="hello"} 1460
telemt_user_octets_from_client{user="hello"} 34554267420 (32.18 GB)
telemt_user_octets_to_client{user="hello"} 623216665188 (580.42 GB)
telemt_user_unique_ips_current{user="hello"} 581
telemt_user_unique_ips_recent_window{user="hello"} 305
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 89601.1 (24h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3729469
telemt_connections_bad_total 336104
telemt_connections_current 1179
telemt_connections_me_current 1179
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 94966
telemt_upstream_connect_attempt_total 54970
telemt_upstream_connect_success_total 54292
telemt_upstream_connect_fail_total 597
telemt_upstream_connect_attempts_per_request{bucket="1"} 54889
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31048
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23068
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 176
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 597
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 6316
telemt_me_reconnect_success_total 2324
telemt_me_reader_eof_total 2254
telemt_me_idle_close_by_peer_total 2254
telemt_me_route_drop_no_conn_total 3573470
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2961272
telemt_me_endpoint_quarantine_total 700
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 692
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 36
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
telemt_me_writers_active_current 94
telemt_desync_total 11714
telemt_desync_full_logged_total 6541
telemt_desync_suppressed_total 5173
telemt_desync_frames_bucket_total{bucket="1_2"} 2707
telemt_desync_frames_bucket_total{bucket="3_10"} 4584
telemt_desync_frames_bucket_total{bucket="gt_10"} 4423
telemt_pool_swap_total 84
telemt_pool_force_close_total 2522
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 212
telemt_me_draining_writers_reap_progress_total 35479
telemt_me_writer_removed_unexpected_total 2205
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4246
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33449
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2160
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 362
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32957
telemt_me_writer_teardown_success_total{mode="normal"} 37695
telemt_me_writer_teardown_noop_total 35479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 71415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 72521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 72801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 73108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 73159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 73172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 73174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 73174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 73174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 73174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 73174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 73174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 73174
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.307459
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 73174
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 212
telemt_me_refill_failed_total 158
telemt_me_writer_restored_same_endpoint_total 2012
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 168
telemt_user_connections_total{user="hello"} 2972148
telemt_user_connections_current{user="hello"} 1179
telemt_user_octets_from_client{user="hello"} 38394126327 (35.76 GB)
telemt_user_octets_to_client{user="hello"} 684864790730 (637.83 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 698
telemt_user_unique_ips_recent_window{user="hello"} 220
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 164460.9 (45h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15677751
telemt_connections_bad_total 1500078
telemt_connections_current 2159
telemt_connections_me_current 2159
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 386828
telemt_upstream_connect_attempt_total 73598
telemt_upstream_connect_success_total 73501
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 73518
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36772
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35040
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1682
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2748
telemt_me_reconnect_success_total 1403
telemt_me_reader_eof_total 1342
telemt_me_idle_close_by_peer_total 1340
telemt_me_route_drop_no_conn_total 13898481
telemt_me_route_drop_channel_closed_total 141
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12498245
telemt_me_endpoint_quarantine_total 1034
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1224
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
telemt_me_writers_active_current 45
telemt_desync_total 51325
telemt_desync_full_logged_total 16124
telemt_desync_suppressed_total 35201
telemt_desync_frames_bucket_total{bucket="1_2"} 11465
telemt_desync_frames_bucket_total{bucket="3_10"} 20010
telemt_desync_frames_bucket_total{bucket="gt_10"} 19850
telemt_pool_swap_total 177
telemt_pool_force_close_total 5997
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 971
telemt_me_draining_writers_reap_progress_total 53993
telemt_me_writer_removed_unexpected_total 1296
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4722
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49858
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5533
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 464
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47996
telemt_me_writer_teardown_success_total{mode="normal"} 54580
telemt_me_writer_teardown_noop_total 54043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 98208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 101567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 103215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 105432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 107020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 108026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 108584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 108614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 108615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 108619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 108621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 108623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 108623
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 305.692689
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 108623
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 971
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 1207
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 12499087
telemt_user_connections_current{user="hello"} 2159
telemt_user_octets_from_client{user="hello"} 181397235713 (168.94 GB)
telemt_user_octets_to_client{user="hello"} 3270327624199 (2.97 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 848
telemt_user_unique_ips_recent_window{user="hello"} 296
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 164462.3 (45h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11316769
telemt_connections_bad_total 1116895
telemt_connections_current 1740
telemt_connections_me_current 1740
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 338924
telemt_upstream_connect_attempt_total 86087
telemt_upstream_connect_success_total 84886
telemt_upstream_connect_fail_total 838
telemt_upstream_connect_attempts_per_request{bucket="1"} 85724
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46056
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34959
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 169
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3702
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 838
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 4070
telemt_me_reconnect_success_total 1684
telemt_me_reader_eof_total 1553
telemt_me_idle_close_by_peer_total 1553
telemt_me_route_drop_no_conn_total 4432792
telemt_me_route_drop_channel_closed_total 490
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8427860
telemt_me_endpoint_quarantine_total 1042
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1244
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
telemt_me_writers_active_current 44
telemt_desync_total 37512
telemt_desync_full_logged_total 12617
telemt_desync_suppressed_total 24895
telemt_desync_frames_bucket_total{bucket="1_2"} 9233
telemt_desync_frames_bucket_total{bucket="3_10"} 14456
telemt_desync_frames_bucket_total{bucket="gt_10"} 13823
telemt_pool_swap_total 174
telemt_pool_force_close_total 5416
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 688
telemt_me_draining_writers_reap_progress_total 52458
telemt_me_writer_removed_unexpected_total 1592
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4855
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49039
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4918
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 498
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47042
telemt_me_writer_teardown_success_total{mode="normal"} 53894
telemt_me_writer_teardown_noop_total 52481
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 99893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 102935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 104049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 105196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 105951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 106290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 106365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 106367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 106373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 106375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 106375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 106375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 106375
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 102.658962
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 106375
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 688
telemt_me_refill_failed_total 129
telemt_me_writer_restored_same_endpoint_total 1442
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 135
telemt_user_connections_total{user="hello"} 8366312
telemt_user_connections_current{user="hello"} 1740
telemt_user_octets_from_client{user="hello"} 208955812501 (194.61 GB)
telemt_user_octets_to_client{user="hello"} 3772403677622 (3.43 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 634
telemt_user_unique_ips_recent_window{user="hello"} 210
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 164426.6 (45h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10653127
telemt_connections_bad_total 917508
telemt_connections_current 1345
telemt_connections_me_current 1345
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 341318
telemt_upstream_connect_attempt_total 71203
telemt_upstream_connect_success_total 70191
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 70373
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33160
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33463
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1454
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4825
telemt_me_reconnect_success_total 1955
telemt_me_reader_eof_total 1706
telemt_me_idle_close_by_peer_total 1705
telemt_me_route_drop_no_conn_total 5199141
telemt_me_route_drop_channel_closed_total 370
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8044306
telemt_me_endpoint_quarantine_total 1116
telemt_me_single_endpoint_outage_enter_total 32
telemt_me_single_endpoint_outage_exit_total 32
telemt_me_single_endpoint_outage_reconnect_attempt_total 33
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 33
telemt_me_single_endpoint_shadow_rotate_total 1209
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 56
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
telemt_desync_total 36993
telemt_desync_full_logged_total 12246
telemt_desync_suppressed_total 24747
telemt_desync_frames_bucket_total{bucket="1_2"} 9356
telemt_desync_frames_bucket_total{bucket="3_10"} 14164
telemt_desync_frames_bucket_total{bucket="gt_10"} 13473
telemt_pool_swap_total 172
telemt_pool_force_close_total 5345
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 695
telemt_me_draining_writers_reap_progress_total 52705
telemt_me_writer_removed_unexpected_total 1849
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5287
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49182
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4802
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 543
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47360
telemt_me_writer_teardown_success_total{mode="normal"} 54469
telemt_me_writer_teardown_noop_total 52776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 101663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 104207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 105129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 106174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 106766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 106978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 107106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 107137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 107145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 107158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 107191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 107194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 107245
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3173.050488
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 107245
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 695
telemt_me_refill_failed_total 152
telemt_me_writer_restored_same_endpoint_total 1691
telemt_me_writer_restored_fallback_total 11
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 147
telemt_user_connections_total{user="hello"} 8037013
telemt_user_connections_current{user="hello"} 1345
telemt_user_octets_from_client{user="hello"} 185768855193 (173.01 GB)
telemt_user_octets_to_client{user="hello"} 3347084376513 (3.04 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 516
telemt_user_unique_ips_recent_window{user="hello"} 191
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 34721.6 (9h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10521887
telemt_connections_bad_total 644874
telemt_connections_current 2290
telemt_connections_me_current 2290
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 212936
telemt_upstream_connect_attempt_total 42188
telemt_upstream_connect_success_total 40071
telemt_upstream_connect_fail_total 1486
telemt_upstream_connect_attempts_per_request{bucket="1"} 41557
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20568
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12192
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5922
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1486
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6283
telemt_me_reconnect_success_total 808
telemt_me_reader_eof_total 512
telemt_me_idle_close_by_peer_total 512
telemt_me_route_drop_no_conn_total 25090675
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8742354
telemt_me_endpoint_quarantine_total 219
telemt_me_single_endpoint_outage_enter_total 60
telemt_me_single_endpoint_outage_exit_total 60
telemt_me_single_endpoint_outage_reconnect_attempt_total 111
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 111
telemt_me_single_endpoint_shadow_rotate_total 274
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
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
telemt_desync_total 13942
telemt_desync_full_logged_total 3638
telemt_desync_suppressed_total 10304
telemt_desync_frames_bucket_total{bucket="1_2"} 2570
telemt_desync_frames_bucket_total{bucket="3_10"} 5655
telemt_desync_frames_bucket_total{bucket="gt_10"} 5717
telemt_pool_swap_total 34
telemt_pool_force_close_total 1284
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 394
telemt_me_draining_writers_reap_progress_total 9779
telemt_me_writer_removed_unexpected_total 714
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1503
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 8948
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1000
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 284
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 8495
telemt_me_writer_teardown_success_total{mode="normal"} 10451
telemt_me_writer_teardown_noop_total 9785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 17180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 18590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 19103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 19767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 20079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 20187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 20236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 20236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 20236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 20236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 20236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 20236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 20236
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 43.918284
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 20236
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 394
telemt_me_refill_failed_total 303
telemt_me_writer_restored_same_endpoint_total 540
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 170
telemt_user_connections_total{user="hello"} 8763968
telemt_user_connections_current{user="hello"} 2290
telemt_user_octets_from_client{user="hello"} 75195564915 (70.03 GB)
telemt_user_octets_to_client{user="hello"} 402707491609 (375.05 GB)
telemt_user_msgs_from_client{user="hello"} 57283
telemt_user_msgs_to_client{user="hello"} 45481
telemt_user_unique_ips_current{user="hello"} 845
telemt_user_unique_ips_recent_window{user="hello"} 320
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 164433.2 (45h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10491989
telemt_connections_bad_total 884455
telemt_connections_current 1976
telemt_connections_me_current 1976
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 232204
telemt_upstream_connect_attempt_total 100018
telemt_upstream_connect_success_total 98967
telemt_upstream_connect_fail_total 895
telemt_upstream_connect_attempts_per_request{bucket="1"} 99862
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60712
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36696
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1321
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 895
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 72182
telemt_me_reconnect_success_total 2709
telemt_me_reader_eof_total 2401
telemt_me_idle_close_by_peer_total 2399
telemt_me_route_drop_no_conn_total 5133686
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8279583
telemt_me_endpoint_quarantine_total 1094
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 40
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 40
telemt_me_single_endpoint_shadow_rotate_total 1226
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 49
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
telemt_me_writers_active_current 51
telemt_desync_total 43814
telemt_desync_full_logged_total 14945
telemt_desync_suppressed_total 28869
telemt_desync_frames_bucket_total{bucket="1_2"} 8899
telemt_desync_frames_bucket_total{bucket="3_10"} 16832
telemt_desync_frames_bucket_total{bucket="gt_10"} 18083
telemt_pool_swap_total 168
telemt_pool_force_close_total 5002
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 622
telemt_me_draining_writers_reap_progress_total 55905
telemt_me_writer_removed_unexpected_total 2441
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5968
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52402
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4307
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 695
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50903
telemt_me_writer_teardown_success_total{mode="normal"} 58370
telemt_me_writer_teardown_noop_total 55906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 112226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 113576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 113960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 114232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 114266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 114269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 114269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 114272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 114276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 114276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 114276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 114276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 114276
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.678625
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 114276
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 622
telemt_me_refill_failed_total 4281
telemt_me_writer_restored_same_endpoint_total 2267
telemt_me_writer_restored_fallback_total 47
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 127
telemt_user_connections_total{user="hello"} 8283187
telemt_user_connections_current{user="hello"} 1976
telemt_user_octets_from_client{user="hello"} 187944895209 (175.04 GB)
telemt_user_octets_to_client{user="hello"} 3134855099436 (2.85 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 719
telemt_user_unique_ips_recent_window{user="hello"} 220
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 101269.3 (28h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10987662
telemt_connections_bad_total 424337
telemt_connections_current 1589
telemt_connections_me_current 1589
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4557773
telemt_upstream_connect_attempt_total 48172
telemt_upstream_connect_success_total 47813
telemt_upstream_connect_fail_total 350
telemt_upstream_connect_attempts_per_request{bucket="1"} 48163
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26515
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21124
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 174
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 350
telemt_me_reconnect_attempts_total 48242
telemt_me_reconnect_success_total 1576
telemt_me_reader_eof_total 1233
telemt_me_idle_close_by_peer_total 1232
telemt_me_route_drop_no_conn_total 3983879
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5286585
telemt_me_endpoint_quarantine_total 657
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 765
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 29520
telemt_desync_full_logged_total 9994
telemt_desync_suppressed_total 19526
telemt_desync_frames_bucket_total{bucket="1_2"} 5926
telemt_desync_frames_bucket_total{bucket="3_10"} 11651
telemt_desync_frames_bucket_total{bucket="gt_10"} 11943
telemt_pool_swap_total 107
telemt_pool_force_close_total 3279
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 340
telemt_me_draining_writers_reap_progress_total 34891
telemt_me_writer_removed_unexpected_total 1294
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3111
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33107
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2856
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 423
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31612
telemt_me_writer_teardown_success_total{mode="normal"} 36218
telemt_me_writer_teardown_noop_total 34898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 69908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 70603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 70889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 71116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 71116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 71116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 71116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 71116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 71116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 71116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 71116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 71116
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.274708
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 71116
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 340
telemt_me_refill_failed_total 2712
telemt_me_writer_restored_same_endpoint_total 1400
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4330
telemt_user_connections_total{user="hello"} 5279692
telemt_user_connections_current{user="hello"} 1589
telemt_user_octets_from_client{user="hello"} 113750891048 (105.94 GB)
telemt_user_octets_to_client{user="hello"} 2009080958018 (1.83 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 574
telemt_user_unique_ips_recent_window{user="hello"} 243
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 82240.0 (22h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1185599
telemt_connections_bad_total 23559
telemt_connections_current 1185
telemt_connections_me_current 1185
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 23086
telemt_upstream_connect_attempt_total 39563
telemt_upstream_connect_success_total 39446
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 39537
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17859
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20960
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 627
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 1775
telemt_me_reconnect_success_total 759
telemt_me_reader_eof_total 734
telemt_me_idle_close_by_peer_total 734
telemt_me_route_drop_no_conn_total 413510
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1051567
telemt_me_endpoint_quarantine_total 696
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 679
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
telemt_me_writers_active_current 43
telemt_desync_total 6058
telemt_desync_full_logged_total 1861
telemt_desync_suppressed_total 4197
telemt_desync_frames_bucket_total{bucket="1_2"} 1398
telemt_desync_frames_bucket_total{bucket="3_10"} 2381
telemt_desync_frames_bucket_total{bucket="gt_10"} 2279
telemt_pool_swap_total 88
telemt_pool_force_close_total 2263
telemt_me_writer_close_signal_drop_total 128
telemt_me_draining_writers_reap_progress_total 32862
telemt_me_writer_removed_unexpected_total 707
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2559
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31039
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2180
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 83
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30599
telemt_me_writer_teardown_success_total{mode="normal"} 33598
telemt_me_writer_teardown_noop_total 32865
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 66264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 66431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 66463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 66463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 66463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 66463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 66463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 66463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 66463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 66463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 66463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 66463
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.000197
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 66463
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 128
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 645
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 1047863
telemt_user_connections_current{user="hello"} 1185
telemt_user_octets_from_client{user="hello"} 19287912953 (17.96 GB)
telemt_user_octets_to_client{user="hello"} 448456301507 (417.66 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 425
telemt_user_unique_ips_recent_window{user="hello"} 188
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 164437.6 (45h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12791359
telemt_connections_bad_total 1486008
telemt_connections_current 1742
telemt_connections_me_current 1742
telemt_handshake_timeouts_total 359727
telemt_upstream_connect_attempt_total 61920
telemt_upstream_connect_success_total 61600
telemt_upstream_connect_fail_total 192
telemt_upstream_connect_attempts_per_request{bucket="1"} 61792
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30388
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31117
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 192
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2434
telemt_me_reconnect_success_total 1295
telemt_me_reader_eof_total 1256
telemt_me_idle_close_by_peer_total 1256
telemt_me_route_drop_no_conn_total 4353532
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 37
telemt_me_route_drop_queue_full_profile_total{profile="high"} 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9679819
telemt_me_endpoint_quarantine_total 1096
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1228
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
telemt_me_writers_active_current 44
telemt_desync_total 39777
telemt_desync_full_logged_total 12975
telemt_desync_suppressed_total 26802
telemt_desync_frames_bucket_total{bucket="1_2"} 9487
telemt_desync_frames_bucket_total{bucket="3_10"} 14699
telemt_desync_frames_bucket_total{bucket="gt_10"} 15591
telemt_pool_swap_total 182
telemt_pool_force_close_total 5019
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 638
telemt_me_draining_writers_reap_progress_total 55684
telemt_me_writer_removed_unexpected_total 1210
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4594
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52336
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4845
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50665
telemt_me_writer_teardown_success_total{mode="normal"} 56930
telemt_me_writer_teardown_noop_total 55686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 110135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 111756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 112123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 112483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 112603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 112616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 112616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 112616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 112616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 112616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 112616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 112616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 112616
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.055248
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 112616
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 638
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 1133
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 9647811
telemt_user_connections_current{user="hello"} 1742
telemt_user_octets_from_client{user="hello"} 188935613684 (175.96 GB)
telemt_user_octets_to_client{user="hello"} 4254830860824 (3.87 TB)
telemt_user_unique_ips_current{user="hello"} 618
telemt_user_unique_ips_recent_window{user="hello"} 194
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 164434.4 (45h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11107012
telemt_connections_bad_total 1254442
telemt_connections_current 1687
telemt_connections_me_current 1687
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 289981
telemt_upstream_connect_attempt_total 87985
telemt_upstream_connect_success_total 87215
telemt_upstream_connect_fail_total 588
telemt_upstream_connect_attempts_per_request{bucket="1"} 87803
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47849
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36402
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 912
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2052
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 588
telemt_me_reconnect_attempts_total 9273
telemt_me_reconnect_success_total 2205
telemt_me_reader_eof_total 2056
telemt_me_idle_close_by_peer_total 2056
telemt_me_seq_mismatch_total 77
telemt_me_route_drop_no_conn_total 5523331
telemt_me_route_drop_channel_closed_total 351
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8583928
telemt_me_endpoint_quarantine_total 1262
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 44
telemt_me_single_endpoint_outage_reconnect_success_total 42
telemt_me_single_endpoint_quarantine_bypass_total 44
telemt_me_single_endpoint_shadow_rotate_total 1229
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 52
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
telemt_me_writers_active_current 42
telemt_desync_total 39042
telemt_desync_full_logged_total 12606
telemt_desync_suppressed_total 26436
telemt_desync_frames_bucket_total{bucket="1_2"} 9713
telemt_desync_frames_bucket_total{bucket="3_10"} 14533
telemt_desync_frames_bucket_total{bucket="gt_10"} 14796
telemt_pool_swap_total 173
telemt_pool_force_close_total 4840
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 623
telemt_me_draining_writers_reap_progress_total 55319
telemt_me_writer_removed_unexpected_total 2083
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5790
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51683
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4384
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 456
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50479
telemt_me_writer_teardown_success_total{mode="normal"} 57473
telemt_me_writer_teardown_noop_total 55324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 110207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 111901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 112428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 112747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 112797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 112797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 112797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 112797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 112797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 112797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 112797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 112797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 112797
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.929061
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 112797
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 623
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 1789
telemt_me_writer_restored_fallback_total 105
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 189
telemt_user_connections_total{user="hello"} 8589710
telemt_user_connections_current{user="hello"} 1687
telemt_user_octets_from_client{user="hello"} 150954759669 (140.59 GB)
telemt_user_octets_to_client{user="hello"} 3299635131855 (3.00 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 650
telemt_user_unique_ips_recent_window{user="hello"} 230
```