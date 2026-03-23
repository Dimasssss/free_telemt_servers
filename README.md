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

# Server Metrics 2026-03-23 05:20:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 116060.8 (32h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4080164
telemt_connections_bad_total 392774
telemt_connections_current 2057
telemt_connections_me_current 2057
telemt_handshake_timeouts_total 135190
telemt_upstream_connect_attempt_total 43169
telemt_upstream_connect_success_total 43168
telemt_upstream_connect_attempts_per_request{bucket="1"} 43168
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15019
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28010
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 96
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_failed_total 5
telemt_me_keepalive_timeout_total 798
telemt_me_reconnect_attempts_total 1497
telemt_me_reconnect_success_total 678
telemt_me_reader_eof_total 698
telemt_me_idle_close_by_peer_total 698
telemt_me_route_drop_no_conn_total 3263280
telemt_me_route_drop_channel_closed_total 1314
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3337267
telemt_me_writer_pick_total{mode="p2c",result="full"} 18
telemt_me_endpoint_quarantine_total 824
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 907
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_desync_total 13920
telemt_desync_full_logged_total 4430
telemt_desync_suppressed_total 9490
telemt_desync_frames_bucket_total{bucket="1_2"} 3619
telemt_desync_frames_bucket_total{bucket="3_10"} 5162
telemt_desync_frames_bucket_total{bucket="gt_10"} 5139
telemt_pool_swap_total 128
telemt_pool_force_close_total 3915
telemt_pool_stale_pick_total 36
telemt_me_writer_close_signal_drop_total 730
telemt_me_draining_writers_reap_progress_total 39555
telemt_me_writer_removed_unexpected_total 672
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2828
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37002
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3850
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 65
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35640
telemt_me_writer_teardown_success_total{mode="normal"} 39830
telemt_me_writer_teardown_noop_total 39568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 73651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 76882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79398
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 423.237130
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79398
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 730
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 608
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 3324864
telemt_user_connections_current{user="hello"} 2057
telemt_user_octets_from_client{user="hello"} 44975333824 (41.89 GB)
telemt_user_octets_to_client{user="hello"} 882720893584 (822.10 GB)
telemt_user_unique_ips_current{user="hello"} 671
telemt_user_unique_ips_recent_window{user="hello"} 514
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 129427.1 (35h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4142710
telemt_connections_bad_total 385308
telemt_connections_current 679
telemt_connections_me_current 679
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 106959
telemt_upstream_connect_attempt_total 80759
telemt_upstream_connect_success_total 79790
telemt_upstream_connect_fail_total 861
telemt_upstream_connect_attempts_per_request{bucket="1"} 80651
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44051
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35512
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 227
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 861
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10938
telemt_me_reconnect_success_total 3904
telemt_me_reader_eof_total 3875
telemt_me_idle_close_by_peer_total 3875
telemt_me_route_drop_no_conn_total 3668168
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3284525
telemt_me_endpoint_quarantine_total 1056
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 54
telemt_me_single_endpoint_outage_exit_total 54
telemt_me_single_endpoint_outage_reconnect_attempt_total 55
telemt_me_single_endpoint_outage_reconnect_success_total 53
telemt_me_single_endpoint_quarantine_bypass_total 55
telemt_me_single_endpoint_shadow_rotate_total 1020
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
telemt_me_writers_active_current 47
telemt_desync_total 13517
telemt_desync_full_logged_total 7621
telemt_desync_suppressed_total 5896
telemt_desync_frames_bucket_total{bucket="1_2"} 3082
telemt_desync_frames_bucket_total{bucket="3_10"} 5299
telemt_desync_frames_bucket_total{bucket="gt_10"} 5136
telemt_pool_swap_total 122
telemt_pool_force_close_total 3391
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 262
telemt_me_draining_writers_reap_progress_total 54212
telemt_me_writer_removed_unexpected_total 3795
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6859
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51190
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2909
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 482
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50821
telemt_me_writer_teardown_success_total{mode="normal"} 58049
telemt_me_writer_teardown_noop_total 54213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 110248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 111526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 111876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 112184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 112247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 112260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 112262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 112262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 112262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 112262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 112262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 112262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 112262
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.944224
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 112262
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 262
telemt_me_refill_failed_total 278
telemt_me_writer_restored_same_endpoint_total 3451
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 49
telemt_me_writer_removed_unexpected_minus_restored_total 313
telemt_user_connections_total{user="hello"} 3298970
telemt_user_connections_current{user="hello"} 679
telemt_user_octets_from_client{user="hello"} 44351556539 (41.31 GB)
telemt_user_octets_to_client{user="hello"} 829759769353 (772.77 GB)
telemt_user_msgs_from_client{user="hello"} 52128
telemt_user_msgs_to_client{user="hello"} 188269
telemt_user_unique_ips_current{user="hello"} 416
telemt_user_unique_ips_recent_window{user="hello"} 201
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 204287.1 (56h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16648586
telemt_connections_bad_total 1687681
telemt_connections_current 1693
telemt_connections_me_current 1693
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 407439
telemt_upstream_connect_attempt_total 91815
telemt_upstream_connect_success_total 91708
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 91725
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44657
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45312
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1732
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3209
telemt_me_reconnect_success_total 1681
telemt_me_reader_eof_total 1639
telemt_me_idle_close_by_peer_total 1637
telemt_me_route_drop_no_conn_total 14110246
telemt_me_route_drop_channel_closed_total 146
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13223596
telemt_me_endpoint_quarantine_total 1381
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1545
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 48
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
telemt_desync_total 55165
telemt_desync_full_logged_total 17632
telemt_desync_suppressed_total 37533
telemt_desync_frames_bucket_total{bucket="1_2"} 12310
telemt_desync_frames_bucket_total{bucket="3_10"} 21603
telemt_desync_frames_bucket_total{bucket="gt_10"} 21252
telemt_pool_swap_total 221
telemt_pool_force_close_total 7095
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1100
telemt_me_draining_writers_reap_progress_total 70654
telemt_me_writer_removed_unexpected_total 1572
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5924
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65588
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6625
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63559
telemt_me_writer_teardown_success_total{mode="normal"} 71512
telemt_me_writer_teardown_noop_total 70708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 130835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 134667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 136481
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 138892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 140559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 141610
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 142181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 142211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 142212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 142216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 142218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 142220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 142220
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 318.938075
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 142220
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1100
telemt_me_refill_failed_total 84
telemt_me_writer_restored_same_endpoint_total 1459
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 105
telemt_user_connections_total{user="hello"} 13223450
telemt_user_connections_current{user="hello"} 1692
telemt_user_octets_from_client{user="hello"} 200101932565 (186.36 GB)
telemt_user_octets_to_client{user="hello"} 3586923686259 (3.26 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 672
telemt_user_unique_ips_recent_window{user="hello"} 261
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 204288.4 (56h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12165332
telemt_connections_bad_total 1290676
telemt_connections_current 966
telemt_connections_me_current 966
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 352336
telemt_upstream_connect_attempt_total 106157
telemt_upstream_connect_success_total 104745
telemt_upstream_connect_fail_total 899
telemt_upstream_connect_attempts_per_request{bucket="1"} 105644
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55528
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45209
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 200
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3808
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 899
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 4679
telemt_me_reconnect_success_total 2012
telemt_me_reader_eof_total 1873
telemt_me_idle_close_by_peer_total 1873
telemt_me_route_drop_no_conn_total 4607895
telemt_me_route_drop_channel_closed_total 504
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8995409
telemt_me_endpoint_quarantine_total 1392
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 1563
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
telemt_me_writers_active_current 47
telemt_desync_total 39564
telemt_desync_full_logged_total 13327
telemt_desync_suppressed_total 26237
telemt_desync_frames_bucket_total{bucket="1_2"} 9820
telemt_desync_frames_bucket_total{bucket="3_10"} 15196
telemt_desync_frames_bucket_total{bucket="gt_10"} 14548
telemt_pool_swap_total 218
telemt_pool_force_close_total 6440
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 722
telemt_me_draining_writers_reap_progress_total 68709
telemt_me_writer_removed_unexpected_total 1904
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6018
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 64457
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5928
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 62269
telemt_me_writer_teardown_success_total{mode="normal"} 70475
telemt_me_writer_teardown_noop_total 68734
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 132422
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 135679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 136834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 138025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 138784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 139124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 139199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 139201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 139207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 139209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 139209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 139209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 139209
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.684552
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 139209
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 722
telemt_me_refill_failed_total 143
telemt_me_writer_restored_same_endpoint_total 1718
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 166
telemt_user_connections_total{user="hello"} 8932991
telemt_user_connections_current{user="hello"} 966
telemt_user_octets_from_client{user="hello"} 219968048068 (204.86 GB)
telemt_user_octets_to_client{user="hello"} 4027424020631 (3.66 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 436
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 204252.3 (56h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11306429
telemt_connections_bad_total 1033751
telemt_connections_current 999
telemt_connections_me_current 999
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 355736
telemt_upstream_connect_attempt_total 90588
telemt_upstream_connect_success_total 89012
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 89217
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40759
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43816
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2068
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2369
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5891
telemt_me_reconnect_success_total 2476
telemt_me_reader_eof_total 2222
telemt_me_idle_close_by_peer_total 2221
telemt_me_route_drop_no_conn_total 5376243
telemt_me_route_drop_channel_closed_total 384
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8503229
telemt_me_endpoint_quarantine_total 1442
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1525
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 72
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
telemt_desync_total 38655
telemt_desync_full_logged_total 12834
telemt_desync_suppressed_total 25821
telemt_desync_frames_bucket_total{bucket="1_2"} 9762
telemt_desync_frames_bucket_total{bucket="3_10"} 14803
telemt_desync_frames_bucket_total{bucket="gt_10"} 14090
telemt_pool_swap_total 214
telemt_pool_force_close_total 6328
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 762
telemt_me_draining_writers_reap_progress_total 69330
telemt_me_writer_removed_unexpected_total 2368
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6759
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 64875
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5757
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63002
telemt_me_writer_teardown_success_total{mode="normal"} 71634
telemt_me_writer_teardown_noop_total 69401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 135182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 137915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 138880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 139953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 140554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 140768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 140896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 140927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 140935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 140948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 140981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 140984
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 141035
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.967945
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 141035
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 762
telemt_me_refill_failed_total 181
telemt_me_writer_restored_same_endpoint_total 2157
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 194
telemt_user_connections_total{user="hello"} 8495053
telemt_user_connections_current{user="hello"} 999
telemt_user_octets_from_client{user="hello"} 194130946663 (180.80 GB)
telemt_user_octets_to_client{user="hello"} 3524686035929 (3.21 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 395
telemt_user_unique_ips_recent_window{user="hello"} 163
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 74532.6 (20h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11642146
telemt_connections_bad_total 695101
telemt_connections_current 1845
telemt_connections_me_current 1845
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 315052
telemt_upstream_connect_attempt_total 67280
telemt_upstream_connect_success_total 63705
telemt_upstream_connect_fail_total 2313
telemt_upstream_connect_attempts_per_request{bucket="1"} 66018
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33190
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22947
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6051
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2313
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 8409
telemt_me_reconnect_success_total 1556
telemt_me_reader_eof_total 982
telemt_me_idle_close_by_peer_total 981
telemt_me_route_drop_no_conn_total 25369176
telemt_me_route_drop_channel_closed_total 60
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9630718
telemt_me_endpoint_quarantine_total 580
telemt_me_single_endpoint_outage_enter_total 111
telemt_me_single_endpoint_outage_exit_total 111
telemt_me_single_endpoint_outage_reconnect_attempt_total 213
telemt_me_single_endpoint_outage_reconnect_success_total 56
telemt_me_single_endpoint_quarantine_bypass_total 213
telemt_me_single_endpoint_shadow_rotate_total 598
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
telemt_me_writers_active_current 67
telemt_desync_total 17256
telemt_desync_full_logged_total 4802
telemt_desync_suppressed_total 12454
telemt_desync_frames_bucket_total{bucket="1_2"} 3344
telemt_desync_frames_bucket_total{bucket="3_10"} 7051
telemt_desync_frames_bucket_total{bucket="gt_10"} 6861
telemt_pool_swap_total 76
telemt_pool_force_close_total 2368
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 529
telemt_me_draining_writers_reap_progress_total 24677
telemt_me_writer_removed_unexpected_total 1439
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3213
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22855
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2042
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 326
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22309
telemt_me_writer_teardown_success_total{mode="normal"} 26068
telemt_me_writer_teardown_noop_total 24696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48557
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 50219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 50708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50764
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 54.847495
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50764
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 529
telemt_me_refill_failed_total 348
telemt_me_writer_restored_same_endpoint_total 997
telemt_me_writer_restored_fallback_total 18
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3153
telemt_me_writer_removed_unexpected_minus_restored_total 424
telemt_user_connections_total{user="hello"} 9658299
telemt_user_connections_current{user="hello"} 1845
telemt_user_octets_from_client{user="hello"} 90624965447 (84.40 GB)
telemt_user_octets_to_client{user="hello"} 718255663389 (668.93 GB)
telemt_user_msgs_from_client{user="hello"} 71666
telemt_user_msgs_to_client{user="hello"} 62721
telemt_user_unique_ips_current{user="hello"} 689
telemt_user_unique_ips_recent_window{user="hello"} 260
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 204259.1 (56h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11272758
telemt_connections_bad_total 992014
telemt_connections_current 1495
telemt_connections_me_current 1495
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 251930
telemt_upstream_connect_attempt_total 119501
telemt_upstream_connect_success_total 118259
telemt_upstream_connect_fail_total 1065
telemt_upstream_connect_attempts_per_request{bucket="1"} 119324
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69370
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 47273
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1378
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1065
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73528
telemt_me_reconnect_success_total 3259
telemt_me_reader_eof_total 2954
telemt_me_idle_close_by_peer_total 2951
telemt_me_route_drop_no_conn_total 5317786
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8875221
telemt_me_endpoint_quarantine_total 1387
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1552
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
telemt_desync_total 47279
telemt_desync_full_logged_total 16255
telemt_desync_suppressed_total 31024
telemt_desync_frames_bucket_total{bucket="1_2"} 9613
telemt_desync_frames_bucket_total{bucket="3_10"} 18129
telemt_desync_frames_bucket_total{bucket="gt_10"} 19537
telemt_pool_swap_total 210
telemt_pool_force_close_total 6050
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 682
telemt_me_draining_writers_reap_progress_total 73368
telemt_me_writer_removed_unexpected_total 2971
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7303
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 69083
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5301
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 67318
telemt_me_writer_teardown_success_total{mode="normal"} 76386
telemt_me_writer_teardown_noop_total 73369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 147599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 149019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 149438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 149711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 149745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 149748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 149748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 149751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 149755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 149755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 149755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 149755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 149755
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.360103
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 149755
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 682
telemt_me_refill_failed_total 4322
telemt_me_writer_restored_same_endpoint_total 2744
telemt_me_writer_restored_fallback_total 56
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7369
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 8877873
telemt_user_connections_current{user="hello"} 1495
telemt_user_octets_from_client{user="hello"} 199006422229 (185.34 GB)
telemt_user_octets_to_client{user="hello"} 3396343136072 (3.09 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 573
telemt_user_unique_ips_recent_window{user="hello"} 211
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 141095.4 (39h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12055361
telemt_connections_bad_total 493399
telemt_connections_current 1060
telemt_connections_me_current 1060
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4868176
telemt_upstream_connect_attempt_total 68485
telemt_upstream_connect_success_total 67996
telemt_upstream_connect_fail_total 476
telemt_upstream_connect_attempts_per_request{bucket="1"} 68472
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35798
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31957
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 241
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 476
telemt_me_reconnect_attempts_total 49358
telemt_me_reconnect_success_total 1960
telemt_me_reader_eof_total 1644
telemt_me_idle_close_by_peer_total 1643
telemt_me_route_drop_no_conn_total 4140420
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5790717
telemt_me_endpoint_quarantine_total 975
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1090
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 32573
telemt_desync_full_logged_total 11142
telemt_desync_suppressed_total 21431
telemt_desync_frames_bucket_total{bucket="1_2"} 6544
telemt_desync_frames_bucket_total{bucket="3_10"} 12827
telemt_desync_frames_bucket_total{bucket="gt_10"} 13202
telemt_pool_swap_total 150
telemt_pool_force_close_total 4240
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 393
telemt_me_draining_writers_reap_progress_total 53340
telemt_me_writer_removed_unexpected_total 1682
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4209
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50869
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3796
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 444
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49100
telemt_me_writer_teardown_success_total{mode="normal"} 55078
telemt_me_writer_teardown_noop_total 53347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 107107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 107888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 108198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 108425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 108425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 108425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 108425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 108425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 108425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 108425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 108425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 108425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 108425
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.833214
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 108425
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 393
telemt_me_refill_failed_total 2753
telemt_me_writer_restored_same_endpoint_total 1730
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5782584
telemt_user_connections_current{user="hello"} 1060
telemt_user_octets_from_client{user="hello"} 121692731800 (113.34 GB)
telemt_user_octets_to_client{user="hello"} 2250991523590 (2.05 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 450
telemt_user_unique_ips_recent_window{user="hello"} 166
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 122066.2 (33h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1685295
telemt_connections_bad_total 37308
telemt_connections_current 798
telemt_connections_me_current 798
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 35675
telemt_upstream_connect_attempt_total 57494
telemt_upstream_connect_success_total 57315
telemt_upstream_connect_fail_total 151
telemt_upstream_connect_attempts_per_request{bucket="1"} 57466
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27161
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29316
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 838
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 151
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 2505
telemt_me_reconnect_success_total 1009
telemt_me_reader_eof_total 1006
telemt_me_idle_close_by_peer_total 1006
telemt_me_route_drop_no_conn_total 563071
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1497494
telemt_me_endpoint_quarantine_total 1038
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1009
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
telemt_desync_total 10327
telemt_desync_full_logged_total 2923
telemt_desync_suppressed_total 7404
telemt_desync_frames_bucket_total{bucket="1_2"} 3247
telemt_desync_frames_bucket_total{bucket="3_10"} 3873
telemt_desync_frames_bucket_total{bucket="gt_10"} 3207
telemt_pool_swap_total 132
telemt_pool_force_close_total 3332
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 178
telemt_me_draining_writers_reap_progress_total 49027
telemt_me_writer_removed_unexpected_total 969
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3699
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46341
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3244
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45695
telemt_me_writer_teardown_success_total{mode="normal"} 50040
telemt_me_writer_teardown_noop_total 49031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 98031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 98803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 99034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 99071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 99071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 99071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 99071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 99071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 99071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 99071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 99071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 99071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 99071
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.684998
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 99071
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 178
telemt_me_refill_failed_total 83
telemt_me_writer_restored_same_endpoint_total 864
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 1493061
telemt_user_connections_current{user="hello"} 798
telemt_user_octets_from_client{user="hello"} 27515347161 (25.63 GB)
telemt_user_octets_to_client{user="hello"} 614016333667 (571.85 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 325
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 204263.6 (56h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13552582
telemt_connections_bad_total 1635351
telemt_connections_current 1504
telemt_connections_me_current 1504
telemt_handshake_timeouts_total 396801
telemt_upstream_connect_attempt_total 82377
telemt_upstream_connect_success_total 82012
telemt_upstream_connect_fail_total 228
telemt_upstream_connect_attempts_per_request{bucket="1"} 82240
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40583
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41323
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 228
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3226
telemt_me_reconnect_success_total 1621
telemt_me_reader_eof_total 1612
telemt_me_idle_close_by_peer_total 1612
telemt_me_route_drop_no_conn_total 4527592
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 44
telemt_me_route_drop_queue_full_profile_total{profile="high"} 44
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10220741
telemt_me_endpoint_quarantine_total 1510
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 1552
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
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
telemt_desync_total 42918
telemt_desync_full_logged_total 13999
telemt_desync_suppressed_total 28919
telemt_desync_frames_bucket_total{bucket="1_2"} 10455
telemt_desync_frames_bucket_total{bucket="3_10"} 15747
telemt_desync_frames_bucket_total{bucket="gt_10"} 16716
telemt_pool_swap_total 226
telemt_pool_force_close_total 5901
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 700
telemt_me_draining_writers_reap_progress_total 74570
telemt_me_writer_removed_unexpected_total 1542
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5727
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 70445
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5727
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 68669
telemt_me_writer_teardown_success_total{mode="normal"} 76172
telemt_me_writer_teardown_noop_total 74572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 148103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 149852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 150235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 150611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 150731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 150744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 150744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 150744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 150744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 150744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 150744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 150744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 150744
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.986885
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 150744
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 700
telemt_me_refill_failed_total 86
telemt_me_writer_restored_same_endpoint_total 1427
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 10187170
telemt_user_connections_current{user="hello"} 1504
telemt_user_octets_from_client{user="hello"} 196944380716 (183.42 GB)
telemt_user_octets_to_client{user="hello"} 4543967111620 (4.13 TB)
telemt_user_unique_ips_current{user="hello"} 538
telemt_user_unique_ips_recent_window{user="hello"} 175
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 204260.3 (56h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11870338
telemt_connections_bad_total 1387096
telemt_connections_current 1146
telemt_connections_me_current 1146
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 319690
telemt_upstream_connect_attempt_total 110226
telemt_upstream_connect_success_total 109279
telemt_upstream_connect_fail_total 738
telemt_upstream_connect_attempts_per_request{bucket="1"} 110017
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59325
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46970
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2071
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 738
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 11074
telemt_me_reconnect_success_total 2759
telemt_me_reader_eof_total 2563
telemt_me_idle_close_by_peer_total 2562
telemt_me_seq_mismatch_total 107
telemt_me_route_drop_no_conn_total 5694845
telemt_me_route_drop_channel_closed_total 355
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9141446
telemt_me_endpoint_quarantine_total 1685
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 56
telemt_me_single_endpoint_outage_exit_total 56
telemt_me_single_endpoint_outage_reconnect_attempt_total 56
telemt_me_single_endpoint_outage_reconnect_success_total 54
telemt_me_single_endpoint_quarantine_bypass_total 56
telemt_me_single_endpoint_shadow_rotate_total 1555
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 58
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
telemt_desync_total 42543
telemt_desync_full_logged_total 13689
telemt_desync_suppressed_total 28854
telemt_desync_frames_bucket_total{bucket="1_2"} 11054
telemt_desync_frames_bucket_total{bucket="3_10"} 15628
telemt_desync_frames_bucket_total{bucket="gt_10"} 15861
telemt_pool_swap_total 216
telemt_pool_force_close_total 5657
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 684
telemt_me_draining_writers_reap_progress_total 74914
telemt_me_writer_removed_unexpected_total 2598
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7135
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 70478
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5186
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 69257
telemt_me_writer_teardown_success_total{mode="normal"} 77613
telemt_me_writer_teardown_noop_total 74919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 149790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 151609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 152163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 152482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 152532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 152532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 152532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 152532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 152532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 152532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 152532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 152532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 152532
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.834822
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 152532
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 684
telemt_me_refill_failed_total 432
telemt_me_writer_restored_same_endpoint_total 2201
telemt_me_writer_restored_fallback_total 142
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 255
telemt_user_connections_total{user="hello"} 9145887
telemt_user_connections_current{user="hello"} 1146
telemt_user_octets_from_client{user="hello"} 159261976692 (148.32 GB)
telemt_user_octets_to_client{user="hello"} 3580248066194 (3.26 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 454
telemt_user_unique_ips_recent_window{user="hello"} 173
```